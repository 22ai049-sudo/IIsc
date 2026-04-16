# VisDrone MOT Assignment Starter

This repository contains a ready-to-run Google Colab notebook:

- `visdrone_mot_assignment_colab.ipynb`

It provides a full **tracking-by-detection** starter pipeline for the IISc VCL assignment:

1. Convert VisDrone DET annotations to COCO format
2. Fine-tune a detector (Torchvision Faster R-CNN)
3. Evaluate detection using `pycocotools`
4. Run a SORT-style tracker on MOT val sequences
5. Evaluate tracking with TrackEval (HOTA, MOTA, IDSW, Precision, Recall)

## Important date clarification
The assignment message says "in a week" but also gives a hard deadline of **Friday, April 17, 2026 at 23:59**. Use the explicit date/time as the final deadline.

## Usage
Open the notebook in Colab, mount your Drive (or upload datasets), adjust dataset paths, and run all cells.
