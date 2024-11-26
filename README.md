# Water Consumption
# Water Usage Prediction from Meter Readings

This project focuses on using machine learning models to predict household water usage patterns based on water meter readings and timestamps. By analyzing water usage data, the goal is to classify water appliances and calculate their respective water usage in gallons.

## Project Overview

The project processes water meter readings and timestamps to identify and classify water usage from different appliances, such as dishwashers, showers, and hoses. Various machine learning models and calibration techniques are employed to improve the accuracy of water usage prediction.

### Key Steps and Files:

1. **Step_1.ipynb**: Initial data processing and exploratory analysis of water meter readings.
2. **Step_2.ipynb**: Feature extraction and preparation for model input.
3. **Step_3.ipynb**: Model training and evaluation for appliance detection.
4. **supervised_learning_model.ipynb**: Implementation of supervised learning techniques for appliance usage classification.
5. **automated_length+fwd.ipynb**: Model for identifying appliance usage based on varying water usage patterns over time.
6. **fixed_length+fwd_distance.ipynb**: A model that uses fixed-length windows and forward distance to determine appliance usage.
7. **calibration_model.ipynb**: Calibration of the model to account for different sensor characteristics or environmental factors.
8. **calibrationdatagenerator_same_input.ipynb**: Calibration data generator for consistent input values across models.
9. **calibrationdatagenerator_varrying_input.ipynb**: Calibration data generator with varying input values.
10. **cascade.ipynb**: Cascade model for multi-step appliance detection.
11. **draft_2_final_variablelength.ipynb**: Final model with variable-length input sequences.
12. **visual_step_1.ipynb**: Visualization of the water meter data and appliance usage.
13. **Untitled13.ipynb**: An experimental notebook for additional modeling or feature exploration.
14. **Copy_of_Step_3.ipynb**: Duplicate of the Step_3 notebook for comparison or further work.

## Requirements

The following Python libraries are required to run the notebooks:

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`
- `tensorflow` (for deep learning models)
- `keras`
- `xgboost`

You can install the required dependencies by running:

```bash
pip install -r requirements.txt
