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
2. Place VisDrone DET train/val and MOT val folders under `/content/visdrone` (or edit paths in the notebook).
3. Run all cells in order.
4. Fill the final metrics dictionary and analysis text before submission.
