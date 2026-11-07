# fitmvp-models

Model files used by the FitMvp Android app for on-device food recognition. This repository contains no app source code.

## aiy_food_v1.tflite

- Model: Google AIY Food classifier V1 (MobileNet-based, 2023 dishes plus a background class).
- Source: Kaggle, `google/aiy`, variation `vision-classifier-food-v1` (https://www.kaggle.com/models/google/aiy/tfLite/vision-classifier-food-v1).
- License: Apache License 2.0 (see `LICENSE` and `NOTICE`). The file is redistributed unmodified.
- Size: 21,151,551 bytes.
- SHA-256: `03dd6d9129501f97be00775d9e17b5d9ad13be730149352adb8f4ca953b7a650`

The file is published as a release asset (see Releases), not committed to the git history.

Known limitation (from the model card): the training set is skewed toward North American food. Do not use the model to determine allergens or nutrition.
