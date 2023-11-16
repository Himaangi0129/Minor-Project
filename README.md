# Minor-Project
Here's a brief summary of the provided code:

1. **Data Import and Exploration:**
   - Imported necessary libraries (pandas, numpy, matplotlib, plotly).
   - Loaded ECG data from a CSV file.
   - Checked for missing values, displayed basic statistics, and explored unique labels.
   - Visualized a sample ECG signal.

2. **Data Preprocessing:**
   - Normalized the data using MinMaxScaler.
   - Applied various filtering techniques (Median, Low-pass, and Wavelet) to the raw signals.
   - Chose the best filtering method (Wavelet) based on Mean Squared Error (MSE) calculations.

3. **Feature Extraction:**
   - Extracted 19 features from the ECG signals.
   - Split the dataset into training and testing sets.
   - Utilized wavelet filtering for feature extraction.
   - Calculated various statistical features from R-peaks, T-peaks, RR-intervals, and QRS durations.

4. **Model Building and Training (LSTM):**
   - Reshaped the data for LSTM model compatibility.
   - Built a simple LSTM model with 64 units and a Dense layer with sigmoid activation.
   - Compiled and trained the model using Adam optimizer and binary crossentropy loss.
   - Evaluated the model on the test set and visualized training/validation error.

5. **Model Evaluation:**
   - Calculated and displayed accuracy, AUC score, and a detailed classification report.
   - Visualized the confusion matrix.

6. **Normal Autoencoder:**
   - Examined time series analysis, moving average, and splitting the dataset.
   - Trained Logistic Regression and SVM models.
   - Evaluated models and displayed confusion matrices.

7. **CNN Model:**
   - Standardized the data.
   - Defined a simple Convolutional Neural Network (CNN) model.
   - Compiled, trained, and evaluated the CNN model.
   - Displayed confusion matrix and classification report.

8. **Overall Result:**
   - Highlighted the effectiveness of the LSTM model in ECG classification.
   - Emphasized the importance of recall in healthcare applications.

This code covers a wide range of tasks, from data preprocessing and feature extraction to building and evaluating different machine learning models for ECG signal classification.
