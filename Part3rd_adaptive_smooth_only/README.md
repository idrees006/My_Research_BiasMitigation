# Adaptive Smooth FixMatch (new method) — CIFAR-10-40

This folder contains the notebook that runs the Adaptive Smooth FixMatch experiment on the CIFAR-10-40 benchmark.

Files included
- Part3rd_adaptive_smooth_only.ipynb — notebook to run the adaptive_smooth-only training pipeline (smoke-test + real run cells included)

How to run
1. Open the notebook in Kaggle / Colab / Jupyter.
2. Use a GPU runtime (Kaggle: Settings -> Accelerator -> GPU T4x2).
3. Run all cells. The notebook includes a quick smoke-test and a longer real-run section.
4. Save the notebook version (Kaggle: Save Version) after the run so checkpoints/results are persisted.

Dependencies
- Python 3.8+
- torch
- torchvision
- numpy
- pillow

Notes
- Checkpoints and results are written to /kaggle/working/checkpoints_adaptive_smooth and /kaggle/working/results_adaptive_smooth.json by default. Adjust paths if running locally.
- If GitHub's notebook preview shows "Invalid Notebook", the file may be malformed JSON. Download the raw file and open it in a local Jupyter/nbformat to validate and re-save if needed.

Author: idrees006

License: (add your preferred license)
