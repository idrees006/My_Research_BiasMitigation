# Smooth FixMatch (paper) — CIFAR-10-40

This folder contains the notebook that runs the Smooth FixMatch experiment on the CIFAR-10-40 benchmark.

Files included
- Part2nd_smooth_fixmatch_only.ipynb — notebook to run the Smooth-FixMatch-only training pipeline (smoke-test + real run cells included)

How to run
1. Open the notebook in Kaggle / Colab / Jupyter.
2. Use a GPU runtime (Kaggle: Settings -> Accelerator -> GPU T4x2). 
3. Run all cells. The notebook has a short smoke-test and a longer real-run section.
4. Save the notebook version (Kaggle: Save Version) after the run so checkpoints/results are persisted.

Dependencies
- Python 3.8+
- torch
- torchvision
- numpy
- pillow

Notes
- Checkpoints and results are written to /kaggle/working/checkpoints_smooth_fixmatch and /kaggle/working/results_smooth_fixmatch.json by default in the notebook. Adjust paths if running locally.

Author: idrees006

License: (add your preferred license)
