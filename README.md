# Sports Video Summarization using Deep Learning

## Overview

This project is a query-driven sports video summarization system that automatically generates personalized match highlights from raw sports footage.

The pipeline combines CNN-based keyframe extraction, YOLO-based event detection, and attention-based scoring to identify the most important gameplay moments while removing redundant clips.

## Features

- Query-driven highlight generation
- CNN-based keyframe extraction
- YOLO event detection
- Attention-based importance scoring
- Reduces redundant frames
- Generates personalized sports highlights

## Tech Stack

- Python
- OpenCV
- PyTorch
- YOLO
- NumPy
- MoviePy
- Matplotlib

## Project Architecture

```
Raw Video
     │
     ▼
CNN Keyframe Extraction
     │
     ▼
YOLO Event Detection
     │
     ▼
Attention Scoring
     │
     ▼
Rank Important Moments
     │
     ▼
Generate Highlight Video
```

## Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Sports-Video-Summarization.git
```

Go into the project directory

```bash
cd Sports-Video-Summarization
```

Install dependencies

```bash
pip install -r requirements.txt
```

## Run

```bash
python app.py
```

or

```bash
python train.py
```

depending on the functionality.

## Results

- Automatically identifies important gameplay moments
- Removes redundant clips
- Generates concise personalized highlights

## Future Improvements

- Real-time streaming support
- Multi-sport compatibility
- Transformer-based temporal modeling
- Audio commentary analysis

## Author

Aditya
<br>
Aryan VK
