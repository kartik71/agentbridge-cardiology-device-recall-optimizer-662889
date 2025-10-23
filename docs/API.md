# API Documentation

## Endpoints
### Device Intake
- **Description**: Collect, validate and normalize demographics from CPOE; attach a runId and timestamp for traceability.
- **Type**: Processing

### Delegate
- **Description**: Execute delegate phase for the Multi-Agent pattern: persist interim state, enforce guardrails, and emit structured JSON results.
- **Type**: Processing

### Handoff
- **Description**: Execute handoff phase for the Multi-Agent pattern: persist interim state, enforce guardrails, and emit structured JSON results.
- **Type**: Processing

### Optimization
- **Description**: Optimization across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Plan Drafting
- **Description**: Plan Drafting across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Documentation
- **Description**: Documentation across joined datasets; branch on thresholds using decision gates; write metrics (success/error counts) for observability.
- **Type**: Processing

### Outcome Measurement
- **Description**: Assemble final payload with status, artifacts, KPIs and audit trail; store to Analytics Lakehouse; return response JSON for the client.
- **Type**: Processing
