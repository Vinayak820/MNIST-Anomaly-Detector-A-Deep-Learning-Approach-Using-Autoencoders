# MNIST-Anomaly-Detector-A-Deep-Learning-Approach-Using-Autoencoders
This project applies deep learning (autoencoders) to detect anomalous handwritten digits in the MNIST dataset. It demonstrates how neural networks can learn data representations and identify outliers without supervision.


Anomaly detection is crucial in scenarios where abnormal behavior needs to be flagged—such as fraud detection, medical imaging, or cybersecurity. In this project, we train an autoencoder to reconstruct normal digit images (like digit 1) and detect anomalies based on reconstruction error. Digits other than 1 are treated as "anomalous."
<br>
<hr>
🛠 Tech Stack
Python 🐍

Jupyter Notebook 📓

TensorFlow/Keras 🤖

NumPy & Matplotlib 📊

MNIST Dataset 📁
<br>
<hr>
🚀 Features
Preprocessing of MNIST dataset

Autoencoder architecture for unsupervised learning

Training on a single digit (e.g., 1) and detecting other digits as anomalies

Visualization of reconstruction vs original images

Histogram analysis of reconstruction error

Threshold-based anomaly decision-making
<br>
<hr>
🧠 How It Works
Data Selection: Only digit 1 images are used for training.

Model Training: A convolutional autoencoder is trained to reconstruct digit 1.

Testing Phase: The model is evaluated on all digits (0-9).

Anomaly Detection: High reconstruction error = anomaly.

Thresholding: A threshold is used to classify a sample as normal or anomalous.
<br>
<hr>
📊 Results
The autoencoder performs well in reconstructing digit 1.

Digits like 0, 2, etc., have visibly worse reconstructions.

Reconstruction error thresholding effectively separates normal vs anomalous digits.
<br>
<hr>
🔮 Future Improvements
Train on multiple digits instead of just one

Try variational autoencoders (VAEs)

Use real-world anomaly datasets (e.g., credit card fraud, medical images)

Evaluate with precision-recall and ROC curves
