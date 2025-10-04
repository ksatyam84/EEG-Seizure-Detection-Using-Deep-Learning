# EEG Seizure Detection Using Deep Learning

## Project Overview
This project implements deep learning models for automatic seizure detection from EEG signals using the CHB-MIT Scalp EEG Database. The pipeline includes data preprocessing, windowing, feature extraction, model training, and evaluation.

## Key Achievements
- Processed over 17,000 EEG windows from 686 records, including 141 with seizures.
- Built and trained deep learning models (EEGNet, LSTM) for binary seizure detection.
- Achieved high performance on test data (example: F1-score > 0.85, ROC AUC > 0.90 on balanced subsets).
- Visualized model performance with ROC curves, confusion matrices, and prediction probability plots.
- Automated data pipeline for reproducible experiments and easy extension to new architectures.

## Project Structure
- `eegfinal.ipynb`, `project.py`: Main scripts for data processing, model training, and evaluation.
- `eegnet_seizure_detection_model.pth`, `best_model.pth`: Saved PyTorch model weights.
- Jupyter notebooks (`eegfinal.ipynb, etc.): Exploratory analysis, model development, and results.
- Plots: `roc_curve.png`, `confusion_matrix.png`, `training_loss.png`, etc.

## How to Run
1. Install requirements: `pip install -r requirements.txt` (see notebooks/scripts for dependencies).
2. Download the CHB-MIT Scalp EEG Database and update the `DATA_DIR` path in scripts.
3. Run `eeg.py` or use the provided notebooks for end-to-end training and evaluation.

## Example Results
- Processed: 17,995 EEG windows
- Models: EEGNet, LSTM
- Test F1-score: >0.85 (on balanced data)
- ROC AUC: >0.90

## Resume Bullet Example
- Developed a deep learning pipeline for seizure detection from EEG, processing 17,000+ windows and achieving >0.85 F1-score and >0.90 ROC AUC on test data using the CHB-MIT Scalp EEG Database.

## References
- [CHB-MIT Scalp EEG Database](https://physionet.org/content/chbmit/1.0.0/)
- [EEGNet: A Compact Convolutional Neural Network for EEG-based Brain–Computer Interfaces](https://arxiv.org/abs/1611.08024)

---
For more details, see the code and notebooks in this repository.
