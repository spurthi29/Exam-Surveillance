# Exam-Surveillance

## Overview

**Exam Surveillance Using Machine Learning** is a project designed to monitor and analyze student behavior during examinations using computer vision and deep learning techniques. This system aims to enhance academic integrity by detecting suspicious activities and generating alerts for further investigation.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Output](#output)
- [License](#license)

## Features

- **Real-time Monitoring:** Captures video streams to monitor student activities during exams.
- **Suspicious Activity Detection:** Utilizes machine learning models to identify behaviors that may indicate cheating.
- **Alert Generation:** Sends notifications for detected anomalies to the supervising authorities.
- **Flexible Input Sources:** Supports various input sources including webcam, video files, and live streams.

## Technologies Used

- **Python** for programming and logic implementation.
- **OpenCV** for video processing and computer vision tasks.
- **PyTorch or TensorFlow** for building and deploying machine learning models.
- **gTTS** for generating audio alerts.
- **Mutagen** for handling audio file formats.
- **Pygame** for playing audio alerts.


## Usage

To run the surveillance system, execute the following command in your terminal:
```bash
python main.py --source <video_source>
```
Replace `<video_source>` with the path to your video file, webcam index, or URL.

### Command-Line Arguments

- `--weights`: Path to the trained model file (e.g., `best.pt`).
- `--source`: Input source for monitoring (e.g., `0` for webcam, `video.mp4` for video file).
- `--imgsz`: Inference size (height, width).
- `--conf-thres`: Confidence threshold for detection.
- `--save-txt`: Save results to text files.
- `--view-img`: Display results in a window.

## Output

- **Monitoring a Live Exam:** Captures real-time activities in an examination hall.
- **Cheating Detection Alerts:** Generates audio alerts when suspicious behavior is detected.



## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

