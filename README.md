# Rwandan Sign Language Translation Model

## Description
This project aims to build a scalable Rwandan Sign Language (RSL) translation model to assist the deaf community in Rwanda. 

This is a prototype that will be translating 50 Isolated RSL signs into text. The model uses LTSM and computer vision techniques like OpenCV and Mediapipe to interpret Rwandan Sign Language videos, process the hand and body gestures, and translate them into their corresponding meanings. 

### Features:
- Translates 50 basic Rwandan Sign Language signs.
- Uses a dataset with video clips of signs ranging between 1-2 seconds.
- Built with technologies: MediaPipe, OpenCV, TensorFlow, LTSM
- User-Friendly Web App: Built using Flask.
  
## Dataset Description
The dataset consists of video recordings of  50 distinct signs, organized into six categories. Each sign has 30 video samples with durations ranging from 1-2 seconds, and each video is split into 30 frames. 

Signs:

1. `Interuro:` – Signs: Amakuru yawe, Muraho, Murakoze, Ni meza, Nitwa, Ntuye, Ukora iki.
2. `Inshinga` – Signs: Guhagarika, Gukunda, Kugira, Kunywa, Kurya, Mfasha, Ndashaka.
3. `Inyuguti` – Signs: All the letters of the alphabet, each represented as a folder labeled with the corresponding letter.
4. `Urabaza` – Signs: Hehe, Inde, Ryari.
5. `Izina` – Signs: Amafaranga, Amata, Ishuli, Rwanda, Umuntu, Umuryango.
6. `Iminsi:` – Signs: Iminsi.


## Setup Instructions
## Demo:
[RSL prototype demo](https://drive.google.com/file/d/192z5KBGZXjVsireCKmFrOvYB1hP_NetG/view?usp=drive_link)
### Clone the repository and follow steps
```bash
git clone https://github.com/Uwimbabazi-Keza/RSL-Project.git

python -m venv venv
source venv/bin/activate

pip install -r requirements.txt

python app.py
```
