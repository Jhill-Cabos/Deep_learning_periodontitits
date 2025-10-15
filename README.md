# Deep Learning for Periodontitis — Progress (PHT)
_Times are Asia/Manila. Use ⭐ for milestones._

---

## YOLOv11

- **Oct 10, 2025 — 10:00 PM**  
  Baseline training on dental images; object detection for periodontal risk.  
  Dataset: _add later_  
  Result (screenshot): _add later_  
  `![result](<paste-image-url>)`

- **Oct 10, 2025 — 11:30 PM**  
  Oversampled **Low Risk** class to address imbalance.  
  Oversampling plot: _add later_  
  Results (metrics screenshot): _add later_  
  `![oversampling](<paste-image-url>)`  
  `![results](<paste-image-url>)`

- ⭐ **Oct 13, 2025 — 2:30 AM**  
  Best so far — hyperparameter tuning (lr, wd, aug).  
  Notebook: _add later_  
  Metrics (screenshot): _add later_  
  `![metrics](<paste-image-url>)`

---

## RF-DETR

- **Oct 15, 2025 — 9:00 PM**  
  Initial setup; verified losses (CE, bbox, GIoU) and training loop.  
  Notebook: _add later_  
  Log / Screenshot: _add later_  
  `![log](<paste-image-url>)`

- **Oct 15, 2025 — 11:00 PM**  
  Tuned augmentation (lower mosaic/mixup), warmup, and weight decay.  
  Before/After metrics (screenshot): _add later_  
  `![before-after](<paste-image-url>)`

- ⭐ **Oct 16, 2025 — 1:30 AM**  
  Best so far — LR sweep + EMA; improved mAP50–95.  
  Config file: _add later_  
  Metrics (screenshot): _add later_  
  `![metrics](<paste-image-url>)`

---

## RT-DETR

- ⭐ **Oct 15, 2025 — 10:00 PM**  
  Best so far — transformer-friendly augmentation + LR schedule.  
  Notebook: _add later_  
  Metrics (screenshot): _add later_  
  `![metrics](<paste-image-url>)`

- **[Add Date & Time]**  
  [Short note of what changed]  
  [Optional screenshot]  
  `![screenshot](<paste-image-url>)`

---

### Quick edit tips
- To add an update, **copy one bullet** block and fill in date, notes, and image URLs.
- You can leave “_add later_” placeholders; they won’t break anything.
- If you want to keep images small, append `?width=420` to GitHub image URLs (works for user-attachments).

---

### New entry template (copy this)
- **[Date — Time]**  
  [What changed (1–2 lines).]  
  [Extra note if needed.]  
  `![label](<paste-image-url>)`
