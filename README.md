# Deep Learning for Periodontitis — Progress Report

## YOLOv11

| Date (PHT) | Change / Notes | Evidence / Links |
|---|---|---|
| **Oct 10, 2025 — 10:00 PM** | Baseline training on dental images (object detection for periodontal risk). Dataset prepared and linked. | Dataset: [Roboflow — Oct 10, 2025](https://app.roboflow.com/team-17/data-aug-eqsa6/5) <br> Result: <br><img src="https://github.com/user-attachments/assets/5a60111b-8c84-49f4-93d3-3364e560ce91" width="360"> |
| **Oct 10, 2025 — 11:30 PM** | Oversampled **Low Risk** class to address imbalance. | Oversampling plot: <br><img src="https://github.com/user-attachments/assets/8674b2e3-5093-48a6-a286-cbc8265063ca" width="360"> <br> Results: <br><img src="https://github.com/user-attachments/assets/d2cb047d-d9ec-4626-bc87-a6c4b22f935b" width="420"> |
| ⭐ **Oct 13, 2025 — 2:30 AM** | Best so far — tuned hyperparameters (lr, wd, aug). | Metrics: <br><img src="https://github.com/user-attachments/assets/b88406df-abc5-4f58-9e46-9d73c91a2777" width="420"> <br> Notebook: [YOLO11_2.ipynb](https://github.com/Jhill-Cabos/Deep_learning_periodontitits/blob/main/YOLO11_2.ipynb) |

---

## RT-DETR

| Date (PHT) | Change / Notes | Evidence / Links |
|---|---|---|
| ⭐ **Oct 15, 2025 — 10:00 PM** | Best so far — added hyperparameters (transformer-friendly aug + LR schedule). | Metrics: <br><img src="https://github.com/user-attachments/assets/9ecc334b-5ec6-4603-a4ff-abaeb957513e" width="520"> <br> Notebook: [RTDETR.ipynb](https://github.com/Jhill-Cabos/Deep_learning_periodontitits/blob/main/RTDETR.ipynb) |

---

## RF-DETR

| Date (PHT) | Change / Notes | Evidence / Links |
|---|---|---|
| **Oct 15, 2025 — 9:00 PM** | Initial RF-DETR setup; verified training loop, losses logging (CE, bbox, GIoU). | Log snippet / screenshot here → <br><img src="<!-- add your image link -->" width="520"> <br> Notebook: [RFDETR.ipynb](https://github.com/Jhill-Cabos/Deep_learning_periodontitits/blob/main/RFDETR.ipynb) |
| **Oct 15, 2025 — 11:00 PM** | Adjusted augmentation (lower mosaic/mixup), tuned warmup & weight decay. | Before/After metrics image → <br> width="420"> |
| ⭐ **Oct 16, 2025 — 1:30 AM** | Best so far — LR sweep + EMA on; improved mAP50-95. | Metrics screenshot → <br>: [results.json](https://github.com/Jhill-Cabos/Deep_learning_periodontitits/blob/main/results.json)" width="420"> <br>


---

