# Audio Classifier

This project uses the **ESC-50 audio dataset**, a well-known dataset for environmental sound classification, sourced from **freesound.org**. The project uses the machine learning techniques of **Random Forests**, **Support Vector Machines (SVM)**, and **Recurrent Neural Network with Long Short-Term Memory (RNN-LSTM)** to classify sounds from the dataset.

- For the **Random Forest** and **SVM** models, I preprocess the data by extracting the **Mel Frequency Cepstral Coefficients (MFCCs)** and collapsing them into a row/column vector.
- For the **RNN-LSTM**, the data is processed separately due to the complex input requirements, involving interleaved **MFCCs**, **delta MFCCs**, and **delta-delta MFCCs** to handle the 3D input shape.

The dataset can be accessed [here](https://github.com/karolpiczak/ESC-50).

K. J. Piczak. ESC: Dataset for Environmental Sound Classification. Proceedings of the 23rd Annual ACM Conference on Multimedia, Brisbane, Australia, 2015.

[DOI: http://dx.doi.org/10.1145/2733373.2806390]
