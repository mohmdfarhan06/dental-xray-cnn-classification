# Data Directory

This directory stores datasets for training, evaluation, and testing.

- `raw/`: Raw X-ray images (downloaded from Kaggle or medical database). Subdirectories by class:
  - `cavity/`
  - `filling/`
  - `implant/`
  - `impacted_tooth/`
- `processed/`: Processed/resized/augmented image data ready for training.
- `sample/`: Sample images for quick validation and test suites.
