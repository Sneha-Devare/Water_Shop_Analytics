# Water Shop Analytics Project
![2204 i607 002 S m012 c12 people drinking water composition isometric](https://github.com/user-attachments/assets/fbb50cf2-ba74-42d5-953b-f1b8a402a05c)


This project is about building a small computer vision system for a water shop using CCTV footage.

Right now this is not final system.  
This is first stage where I tried to make full ML pipeline working properly.

Model tries to detect:
- person  
- water can  

Main aim was to understand how dataset, annotation and YOLO training works step by step.

---

## What I did in this project

- Took few frames from CCTV video  
- Selected useful images manually  
- Annotated person and water can using CVAT tool  
- Exported labels in YOLO format  
- Created dataset folders (train and val)  
- Trained YOLO model for testing  
- Checked prediction on sample images  

At this stage dataset is very small and training only 1 epoch.  
So accuracy is not main focus.  
Goal was just to confirm pipeline is working end to end.

---

## Folder structure

Water_Shop_Analytics  
│  
├── Water_Shop_Analytics_Final.ipynb  
├── dataset  
│   ├── images  
│   │   ├── train  
│   │   └── val  
│   ├── labels  
│   │   ├── train  
│   │   └── val  
│   └── data.yaml  

---

## Classes used

0 = person  
1 = water_can  

---

## Tools used

- Python  
- Google Colab  
- YOLOv8  
- OpenCV  
- CVAT  
- GitHub  

---

## Training details

- Model used: YOLOv8n  
- Images: small sample images  
- Epochs: 1  
- Purpose: only pipeline testing  

Model is not trained for high accuracy yet.  
More images and more epochs needed for proper detection.  
This stage was only for pipeline verification.

---

## Future work

- Add more images  
- Train model properly  
- Run detection on full CCTV video  
- Count customers and cans  
- Build analytics system  

---

## About me

Sneha Devare  
BSc Computer Science (Data Science & Analytics)

This project I made to learn computer vision pipeline and understand how real ML workflow works step by step.


