# Pull-Up-Counter-Edited-Video
# Pull-Up Rep Counter

A computer vision project that detects and counts pull-up repetitions from video using pose estimation.

## Features

* Human pose detection using YOLO Pose
* Elbow angle-based movement analysis
* Automatic pull-up repetition counting
* Movement state detection (UP/DOWN)
* Skeleton and counter overlay on the output video

## Workflow

```text
Input Video
    ↓
YOLO Pose Estimation
    ↓
Keypoint Extraction
    ↓
Elbow Angle Analysis
    ↓
Movement State Detection
    ↓
Rep Counter
    ↓
Annotated Output Video
```

## Requirements

* Google Colab
* Python 3
* Ultralytics YOLO
* OpenCV
* NumPy

## Usage

Run the notebook cells sequentially, upload a pull-up video when prompted, and the processed video will be generated automatically.

The resulting video contains the detected pose, repetition counter, movement state, and elbow angle.

## Notes

This is an experimental implementation. Counting accuracy depends on camera angle, body visibility, lighting, and pose detection quality.
