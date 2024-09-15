# Its-A-Shark 🦈

**Its-A-Shark** is a cutting-edge project aimed at improving beach safety by identifying sharks in real-time using advanced machine learning models. The system helps to alert lifeguards and beachgoers before a potential shark attack, providing detailed information on shark type and proximity to shore.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Tech Stack](#tech-stack)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Future Enhancements](#future-enhancements)
7. [Contributing](#contributing)
8. [License](#license)

## Project Overview
Shark attacks, though rare, can be catastrophic for beachgoers. **Its-A-Shark** leverages AI-driven shark detection using video or camera footage to identify different species of sharks near the shore, and promptly alerts lifeguards. The goal is to provide ample warning time to potentially prevent attacks, enhancing beach safety.

## Features
- **Real-time Shark Detection**: Identifies sharks from video streams or static images using trained models.
- **Species Classification**: Uses deep learning to classify the species of the shark detected.
- **Automated Alerts**: Sends warnings to lifeguards about shark presence and type.
- **User-Friendly Interface**: Displays real-time video footage along with detected shark details.
- **Scalable**: Can be expanded to include more marine animals or additional alert features.

## Tech Stack
- **Machine Learning Models**: 
  - [Voxel51](https://voxel51.com/): Used to preprocess and prepare the data, making it more compatible and optimized for training machine learning models.
  - [Ultralytics YOLOv5nu](https://ultralytics.com/yolov5): A variant of the YOLOv5 model, specifically trained to detect sharks in the water and identify the type of shark.

- **Languages**: 
  - Python

- **Development Tools**:
  - Git & GitHub (version control)
  - Jupyter Notebooks (for experimentation)
