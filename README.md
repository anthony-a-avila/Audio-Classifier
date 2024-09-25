# Audio Classifier Project

## Description
This project uses the **ESC-50 audio dataset**, a well-known dataset for environmental sound classification, sourced from **freesound.org**. The project applies machine learning techniques such as **Support Vector Machines (SVM)**, **Random Forests**, and **Recurrent Neural Networks (RNN-LSTM)** to classify sounds from the dataset.

- For the **SVM** and **Random Forest** models, I preprocess the data by extracting the **Mel Frequency Cepstral Coefficients (MFCCs)** and collapsing them into a row/column vector.
- For the **RNN-LSTM**, the data is processed separately due to the complex input requirements, involving interleaved **MFCCs**, **delta MFCCs**, and **delta-delta MFCCs** to handle the 3D input shape.

## Work in Progress 🚧
The current version of the code does not work fully due to the absence of the dataset in the repository. I'm working on updating the project to automatically download the dataset from an external source by 09/26/2024.

### To-Do:
- [ ] Implement dataset download functionality.

The dataset can be accessed [here](https://github.com/karolpiczak/ESC-50).
