# YOLOV8 Drivesafe Model with WASM JS Worker

<p align="center">
  <img src="public/demo.gif" alt="animated" />
</p>

This is a web application that uses the YOLOV8 object detection model with WebAssembly (WASM) and a JavaScript Worker to perform real-time object detection on video streams.

## You can try the live demo here 👇
https://yolov-8-web-inference-with-wasm.vercel.app/

## Features
- Real-time object detection using the YOLOV8 model
- Utilizes WebAssembly (WASM) for efficient model inference
- JavaScript Worker for offloading computations and improving performance
- Detects features related to driver drowsiness, such as "eyes open", "front face" and "yawn".
## Instructions

1. To install dependencies:

```bash
   bun install
```

2. Run bun server:

```bash
bun run index.tsx
```

3. Navigate to:
   http://localhost:3000/index.html

4. Usage: Grant permission to access your webcam when prompted.
