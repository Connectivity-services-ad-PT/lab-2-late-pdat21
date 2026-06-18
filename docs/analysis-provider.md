## Provider Analysis - Camera AI Vision (Pair 02)

### Responsibilities
- Process camera frames
- Detect objects in images
- Generate alerts based on detection

### Inputs
- FrameRequest:
  - cameraId
  - timestamp
  - imageUrl (optional)

### Outputs
- Detection list
- Alert list
- Event stream

### Constraints
- Low latency processing
- Support real-time stream
- Accuracy > 90%

### Dependencies
- None (source system)