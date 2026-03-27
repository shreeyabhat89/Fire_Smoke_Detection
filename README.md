
# Fire & Smoke Detection using Custom Annotated Dataset

# Project Overview

This project demonstrates the development of a fire and smoke detection system using a custom-built dataset created and annotated from scratch.

The primary goal was to understand the importance of *high-quality data annotation* in object detection tasks and how it directly impacts model performance.

---

# Dataset Details

* Total Images: 100
* Classes: Fire , Smoke 
* Annotation Tool: Roboflow

The dataset includes real-world challenging scenarios:

* Low visibility smoke
* Small and distant fire regions
* Complex backgrounds



# Annotation Process (Core Strength)

All images were manually annotated with high attention to detail:

* Accurate bounding boxes for fire and smoke
* Maintained consistency across all images
* Carefully handled edge cases:

  * Smoke vs fog confusion
  * Reflections mistaken as fire
  * Partial or occluded fire regions

 This ensures high-quality training data for object detection models.

---

# Model Training

* Model: Roboflow RF-DETR object detection (Nano)
* Trained on custom annotated dataset

---

# Results

* mAP@50: 62.2%
* Precision: 78.3%
* Recall: 63.1%

 Note: Results are based on a small dataset and highlight the importance of dataset scaling and annotation quality.

---

# Error Analysis

Key observations from model predictions:

* Missed small or faint smoke regions
* Confusion between fog and smoke
* Reduced performance in low-light conditions
* Bright sunlight vs fire
* False negatives in low-light conditions

---

# Key Learnings

* Data annotation quality significantly impacts model performance
* Precision improves with accurate bounding boxes
* Increasing dataset size can improve recall

---

# Visual References

![Screenshot_27-3-2026_211034_app roboflow com](https://github.com/user-attachments/assets/ef74257b-d56c-433c-8cc0-809d2a37a737)
![Screenshot_27-3-2026_21951_app roboflow com](https://github.com/user-attachments/assets/6615f4f8-e84d-477b-a722-223f03e3f53a)
![Screenshot_27-3-2026_211010_app roboflow com](https://github.com/user-attachments/assets/e72cac72-feaf-4ad8-a8d3-739bb94b86d4)
![Screenshot_27-3-2026_211022_app roboflow com](https://github.com/user-attachments/assets/ee493b92-759a-44a0-a3d1-37631a5d9988)
![Screenshot_27-3-2026_205022_app roboflow com](https://github.com/user-attachments/assets/a655db8e-379e-47f4-8fb8-93902624e21c)
![Screenshot_27-3-2026_205150_app roboflow com](https://github.com/user-attachments/assets/743a5335-9c60-4e90-a228-be33113606df)
![Screenshot_27-3-2026_205222_app roboflow com](https://github.com/user-attachments/assets/0363037f-b5b0-4cff-ae12-76a64d05e9b9)
![Screenshot_27-3-2026_205314_app roboflow com](https://github.com/user-attachments/assets/9277501c-6535-4d23-afd4-8537fb706cb1)
![Screenshot_27-3-2026_205515_app roboflow com](https://github.com/user-attachments/assets/6fc2f6c4-39ae-45ee-8f3e-53fec4d3cf09)
<img width="667" height="667" alt="Screenshot 2026-03-27 214926" src="https://github.com/user-attachments/assets/219ef39b-e927-478b-a5ae-515ed4a6eaf6" />
<img width="672" height="667" alt="Screenshot 2026-03-27 214800" src="https://github.com/user-attachments/assets/ee25a954-b609-418d-be9e-e21a67ffe6a9" />
<img width="667" height="672" alt="Screenshot 2026-03-27 214654" src="https://github.com/user-attachments/assets/192f2620-c55d-4220-8410-c67c13f5a935" />
<img width="677" height="672" alt="Screenshot 2026-03-27 214624" src="https://github.com/user-attachments/assets/0c816d7f-d52a-4862-8cb0-6808aac9bbbb" />
<img width="667" height="675" alt="Screenshot 2026-03-27 214549" src="https://github.com/user-attachments/assets/99dc50c4-a980-4ce8-bdf2-0eb9859ee54c" />
<img width="683" height="676" alt="Screenshot 2026-03-27 214514" src="https://github.com/user-attachments/assets/42815594-92d0-42ad-9006-2bd575891dc3" />
<img width="672" height="680" alt="Screenshot 2026-03-27 215100" src="https://github.com/user-attachments/assets/08e98bc7-d058-4f13-bd94-c80e269035e4" />

# Why this project matters

This project showcases my ability to:

* Perform high-quality data annotation
* Handle real-world edge cases
* Understand dataset challenges in computer vision
* Analyze model performance

---

##Let's Work Together

I am open to freelance opportunities in:

* Data Annotation
* Image Labeling
* Computer Vision Projects

---
