# VisDrone Assignment Notebook (IISc VCL)

This repo contains a single Colab-ready notebook:

- `visdrone_mot_assignment_colab.ipynb`

## What's unique in this version
- Uses a **RetinaNet** detector (torchvision, non-proprietary).
- Uses a custom **ByteTrack-style** tracker (`ByteLiteTracker`) with high/low confidence association.
- Includes DET conversion, training, pycocotools evaluation, MOT metrics, and TrackEval HOTA flow in one place.

## Deadline clarification
Use the explicit deadline from the assignment text:
**Friday, April 17, 2026, 23:59**.

## How to use
1. Open notebook in Colab (GPU runtime).
2. Upload the three ZIPs to Colab `/content`: `VisDrone2019-DET-train.zip`, `VisDrone2019-DET-val.zip`, `VisDrone2019-MOT-val.zip`.
3. Run the extraction cell in the notebook (it validates exact folder names).
4. Run remaining cells in order and fill final metrics/analysis.

