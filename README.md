<h1>Deep Learning for Periodontitis — 3-Column Progress</h1>

<table>
  <thead>
    <tr>
      <th>YOLOv11</th>
      <th>RF-DETR</th>
      <th>RT-DETR</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <!-- YOLOv11 COLUMN -->
      <td>
        <ul>
          <li>
            <b>Oct 10, 2025 — 10:00 PM</b><br/>
            Baseline training on dental images; object detection for periodontal risk.<br/>
            Dataset: <a href="https://app.roboflow.com/team-17/data-aug-eqsa6/5">Roboflow — Oct 10, 2025</a><br/>
            <details><summary>Result (screenshot)</summary>
              <img src="https://github.com/user-attachments/assets/5a60111b-8c84-49f4-93d3-3364e560ce91" width="360"/>
            </details>
          </li>

          <li>
            <b>Oct 10, 2025 — 11:30 PM</b><br/>
            Oversampled <b>Low Risk</b> class to address imbalance.<br/>
            <details><summary>Oversampling plot</summary>
              <img src="https://github.com/user-attachments/assets/8674b2e3-5093-48a6-a286-cbc8265063ca" width="360"/>
            </details>
            <details><summary>Results</summary>
              <img src="https://github.com/user-attachments/assets/d2cb047d-d9ec-4626-bc87-a6c4b22f935b" width="420"/>
            </details>
          </li>

          <li>
            ⭐ <b>Oct 13, 2025 — 2:30 AM</b><br/>
            Best so far — hyperparameter tuning (lr, wd, aug).<br/>
            <a href="https://github.com/Jhill-Cabos/Deep_learning_periodontitits/blob/main/YOLO11_2.ipynb">YOLO11_2.ipynb</a>
            <details><summary>Metrics</summary>
              <img src="https://github.com/user-attachments/assets/b88406df-abc5-4f58-9e46-9d73c91a2777" width="420"/>
            </details>
          </li>
        </ul>
      </td>

      <!-- RF-DETR COLUMN -->
      <td>
        <ul>
          <li>
            <b>Oct 15, 2025 — 9:00 PM</b><br/>
            Initial setup; verified losses (CE, bbox, GIoU) and training loop.<br/>
            Notebook: <a href="<!-- add your RFDETR notebook link -->">RFDETR.ipynb</a>
            <details><summary>Log/Screenshot</summary>
              <img src="<!-- add link to RF-DETR log image -->" width="420"/>
            </details>
          </li>

          <li>
            <b>Oct 15, 2025 — 11:00 PM</b><br/>
            Tuned aug (lower mosaic/mixup), warmup & weight decay.<br/>
            <details><summary>Before/After metrics</summary>
              <img src="<!-- add link to RF-DETR before/after metrics -->" width="420"/>
            </details>
          </li>

          <li>
            ⭐ <b>Oct 16, 2025 — 1:30 AM</b><br/>
            Best so far — LR sweep + EMA; improved mAP50–95.<br/>
            Config: <a href="<!-- add link if committed -->">rf-detr-config.yaml</a>
            <details><summary>Metrics</summary>
              <img src="<!-- add link to RF-DETR best metrics image -->" width="420"/>
            </details>
          </li>
        </ul>
      </td>

      <!-- RT-DETR COLUMN -->
      <td>
        <ul>
          <li>
            ⭐ <b>Oct 15, 2025 — 10:00 PM</b><br/>
            Best so far — transformer-friendly aug + LR schedule.<br/>
            Notebook: <a href="https://github.com/Jhill-Cabos/Deep_learning_periodontitits/blob/main/RTDETR.ipynb">RTDETR.ipynb</a>
            <details><summary>Metrics</summary>
              <img src="https://github.com/user-attachments/assets/9ecc334b-5ec6-4603-a4ff-abaeb957513e" width="520"/>
            </details>
          </li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
