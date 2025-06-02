# LstmCnnModel_hooman

This repository implements a hybrid neural network architecture combining LSTM (Long Short-Term Memory) and CNN (Convolutional Neural Network) models for gold price prediction (gold pred task). The code is designed for ease of experimentation and learning, with detailed comments provided to guide you through data preparation, model configuration, training, and evaluation.

## Task

**Gold Price Prediction**  
The main task addressed by this repository is predicting gold prices using time-series data and a combined LSTM-CNN approach.

## Main Packages Used

- `torch`, `torch.nn`, `torch.optim` (PyTorch for model building and training)
- `torch.utils.data` (for DataLoader and TensorDataset)
- `pandas` and `numpy` (for data manipulation)
- `sklearn.metrics` (for R^2 score and other evaluation metrics)
- `matplotlib.pyplot` (for plotting results)

## Usage Instructions

**Please read the comments within the code files to learn how to work with this repository.**  
Every step is thoroughly commented—from data loading to model evaluation—so users can follow and adapt the workflow for their own data or experiments.

### Steps Overview

1. Prepare your dataset as per the instructions in the code comments.
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the main script to train and evaluate the model.
4. Review the comments and output for insights and next steps.

## Results

The LSTM-CNN hybrid approach achieved the following results on the gold price prediction task:

- **R² Score:** 0.9839
- **Test RMSE:** 39.7411
- **Test RMAE:** 5.5616
- **Test MAPE:** 1.24%

These metrics demonstrate a very strong performance for the model on this task.

## Requirements

- Python 3.x

## Notes

- All code is extensively commented. **Refer to the comments for a comprehensive guide on how to use and modify the code.**
- You can adapt the model and workflow to similar time-series prediction tasks by following the provided guidelines in the comments.

## License

This project is licensed under the MIT License.

---

For questions or issues, please open an issue in this repository.
