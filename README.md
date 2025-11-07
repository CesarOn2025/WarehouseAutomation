# Warehouse Automation

**Team Members:** Cesar Noriega Martinez  
**Project Tier:** Tier 2 – Moderate complexity, practical impact

## 🧩 Problem Statement

Workers spend hours manually counting inventory, especially items with similar appearance but different sizes.

## 💡 Solution Overview

Computer vision system that detects and counts inventory items using YOLOv8.

## 🛠️ Technical Approach

- **Technique:** Object Detection  
- **Model:** YOLOv8  
- **Framework:** PyTorch + Ultralytics

## 🗂️ Dataset Plan

- **Source:** Roboflow or custom image collection  
- **Size:** ~1,000 images  
- **Labels:** Elbow type and size (e.g., small, medium, large)  
- **Preparation:** Manual labeling using Roboflow tools

## 📊 Metrics

- **Primary Metric:** Detection Accuracy ≥ 90%  
- **Secondary Metric:** Latency < 1 second per image

## 📅 Week-by-Week Plan

| Week | Task                        | Milestone        |
|------|-----------------------------|------------------|
| 10   | Get dataset, set up env     | Dataset ready    |
| 11   | Train/fine-tune YOLOv8      | Model working    |
| 12   | Test and improve            | Good accuracy    |
| 13   | Create demo/video           | Demo ready       |
| 14   | Final testing/docs          | Everything done  |
| 15   | Present project             | 🎉 Presentation  |

## 🧰 Resources Needed

- **Compute:** Google Colab  
- **Frameworks:** PyTorch, Ultralytics  
- **Estimated Cost:** $0–$10 (if using paid APIs)

## ⚠️ Risks & Mitigation

| Risk             | Probability | Mitigation                          |
|------------------|-------------|-------------------------------------|
| Low accuracy     | Medium      | Use data augmentation               |
| Missing data     | High        | Use Roboflow public dataset         |
| Similar items    | Medium      | Add size classification post-YOLO  |

## 🤖 AI Usage Log

Used Copilot to generate README structure, organize proposal slides, and guide repository setup.

