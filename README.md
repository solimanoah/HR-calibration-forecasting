# HR-calibration-forecasting

## Project Overview

For a complete overview of the project, see [HR_CALIBRATION_FORECASTING_README.pdf](./HR_CALIBRATION_FORECASTING_README.pdf).

For a more raw and comprehensive overview of the project and its data, see [HR_CALIBRATION_FORECASTING_COMPREHENSIVE_README.pdf](./HR_CALIBRATION_FORECASTING_COMPREHENSIVE_README.pdf).

## Data Retrieval

To view the PPG-DaLiA dataset, [visit here](https://archive.ics.uci.edu/dataset/495/ppg+dalia)

## How to Run

The complete training and evaluation process is implemented in the Colab notebook: [HR_calibration_and_forecasting.ipynb](./HR_calibration_and_forecasting.ipynb)

To reproduce results:
1. Open the notebook in **Google Colab**.
2. Download the required dataset files (`S1.pkl`-`S15.pkl` and their corresponding `S*_activity.csv` files) from the PPG-DaLiA dataset.
3. Upload them to your Google Drive using a similar directory structure used in the notebook (e.g. `/MyDrive/PPG_DaLiA/subjects/`).
4. Update any Drive paths if your setup differs.
5. Run all cells sequentially to preprocess data, train, and evaluate the model.
