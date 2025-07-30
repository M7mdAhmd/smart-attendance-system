# Face Attendance System

A real-time face recognition attendance system built with:

- **ONNX (YuNet)** for fast and accurate face detection
- **DeepFace** for facial embedding generation and verification
- **FAISS** for high-speed similarity search across known faces
- **OpenCV** for video capture and user interface
- **CSV logging** for automated attendance records by date

## Features

- Real-time face detection and recognition via webcam
- Stores daily attendance in CSV format, preventing duplicates
- Scalable face search using FAISS (suitable for large datasets)
- Supports ONNX-based face detection with low latency
- Easy to extend and integrate with GUI or cloud backend

## Dependencies

- Python 3.8+
- OpenCV (`opencv-contrib-python`)
- DeepFace
- FAISS
- NumPy