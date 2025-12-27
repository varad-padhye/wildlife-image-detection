# Wildlife Grid Detection using Hand-Crafted Features

## Project Overview
This project implements a machine learning pipeline to detect **regions containing wild-life (animals, birds, insects)** in images provided in the dataset:

https://tinyurl.com/E7-IMAGES-DS203-2025-S1

Each image is processed, divided into an **8 × 8 grid**, and a binary label is predicted for every grid cell:
- **1** → contains wild-life  
- **0** → does not contain wild-life  

The final output includes:
- Visually highlighted grid cells containing wild-life
- A CSV file containing predictions for all 64 grid cells per image

---

## Directory Structure
