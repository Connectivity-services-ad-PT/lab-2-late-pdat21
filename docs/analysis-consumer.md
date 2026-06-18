## Consumer Analysis - Camera AI Vision (Pair 02)

### Consumers
- Core System
- Analytics Engine

### APIs Used
- GET /detections
- GET /alerts
- GET /events

### Data Usage
- Detection used for monitoring
- Alerts used for notification
- Events used for analytics pipeline

### Requirements
- Response must be consistent schema
- Must support real-time polling
- Must handle missing/null metadata

### Risks
- High traffic on /events
- Data duplication in stream