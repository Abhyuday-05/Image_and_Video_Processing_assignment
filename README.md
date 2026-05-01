# Image and Video Processing Assignment

## Brief Description

This project implements a machine learning pipeline for image/video classification, focusing on distinguishing between **High pT (HiPt)** and **Low pT (LoPt)** samples. The workflow includes data preprocessing, model training, and evaluation using a neural network-based approach. Performance is assessed using ROC curves and AUC scores.

## Project Structure

* `train.py` – Trains the neural network model on the dataset and saves training loss plots.
* `model.py` – Defines the neural network architecture used for classification.
* `dataset.py` – Handles data loading, preprocessing, and batching.
* `config.py` – Stores hyperparameters and configuration settings.
* `predict.py` – Runs inference on test data and generates evaluation metrics.
* `interface.py` – Provides a simple interface for interacting with the trained model.
* `checkpoints/bestmodel.pth` – Saved weights of the best performing model.
* `training_loss.png` – Plot of training loss over epochs.
  


## Testing / Inference

To evaluate the model and run predictions:

```bash id="xw1b7a"
python predict.py
```

During testing, the model performs **HiPt vs LoPt classification**, and the **ROC curve is plotted along with the computation of AUC (Area Under the Curve)**.

## Requirements

Make sure all dependencies are installed in your environment before running the code (e.g., PyTorch, NumPy, Matplotlib, scikit-learn).

## Notes

* Ensure `checkpoints/bestmodel.pth` is present before running inference.
* Run all scripts from the root of the project directory.
* Note that everything works for me. I have followed all instructions to the best of my understanding.
* For any queries, contact me via email- abhyuday.pandey@students.iiserpune.ac.in
