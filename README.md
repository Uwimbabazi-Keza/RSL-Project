# Rwandan Sign Language Translation Model

## Description
This project aims to build a scalable Rwandan Sign Language (RSL) translation model to assist the deaf community in Rwanda. 

This is a prototype that will be translating 10 specific RSL signs into text. The model uses LTSM and computer vision techniques like Mediapipe to interpret Rwandan Sign Language videos, process the hand and body gestures, and translate them into their corresponding meanings. 

### Features:
- Translates 10 basic Rwandan Sign Language signs.
- Uses a dataset with video clips of signs ranging between 1-2 seconds.
- Built with technologies: MediaPipe, OpenCV, TensorFlow, LTSM
  
## Dataset Description
The dataset consists of video recordings of 10 Rwandan Sign Language signs. Each sign has 30 video samples with durations ranging from 1-2 seconds, and each video is split into 30 frames. The dataset is organized into 10 folders, each representing a specific RSL sign. Each folder contains 30 video clips of the corresponding sign. 

Signs:

1. `Amata` – Milk
2. `Murakoze` – Thank you
3. `Amakuru yawe` – How are you
4. `Guhagarika` – Stop
5. `Umuntu` – Person
6. `Gushaka` – Want
7. `Kugira` – To have
8. `Rwanda` – Rwanda
9. `Ishuri` – School
10. `Muraho` – Hello


## Setup Instructions
## Demo:
[RSL prototype demo](https://drive.google.com/file/d/1LWldX1ULsrFSV-7RmwCetpERsO9clpey/view?usp=sharing)
### Clone the repository
```bash
git clone https://github.com/Uwimbabazi-Keza/RSL-Project.git

pip install numpy mediapipe tensorflow

python Test_GUI.py

