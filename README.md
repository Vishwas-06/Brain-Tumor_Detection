# Brain-Tumor_Detection
"Brain Tumor Classification System: Uses CNNs to categorize brain scans into Normal, Pituitary, Glioma, or Meningioma tumors, aiding medical diagnosis." 


The Brain Tumor Classification System is a machine learning project that uses convolutional neural networks (CNNs) to classify brain tumor images into four different categories: Normal, Pituitary Tumor, Glioma Tumor, and Meningioma Tumor. This system is designed to assist medical professionals in diagnosing brain tumors more efficiently.

Key Features:

Data Preparation: The project begins by loading and preprocessing brain tumor images from a dataset, which includes images of both tumor and non-tumor cases. These images are resized to a uniform size of 128x128 pixels.

Data Labeling: Each image is labeled with its corresponding tumor type using one-hot encoding. The four tumor types are mapped to the following labels: 0 (Normal), 1 (Pituitary Tumor), 2 (Glioma Tumor), and 3 (Meningioma Tumor).

Model Architecture: The neural network model is implemented using the Keras library. It consists of multiple convolutional layers, batch normalization, max-pooling layers, dropout layers, and fully connected layers to extract features and make predictions.

Training: The model is trained on the labeled image dataset using the categorical cross-entropy loss function and the Adamax optimizer. Training is performed over 20 epochs with a batch size of 200.

User Interface: The project includes a graphical user interface (GUI) built using the Tkinter library. Users can interact with the system by providing their name and, optionally, uploading their own brain scan images for classification.

Classification Results: Upon uploading a brain scan image, the system classifies the tumor type and displays the results on the GUI. Users can view detailed information about the detected tumor type and related medical information.

Image Visualization: The system also allows users to view the uploaded brain scan image alongside the classification results for better understanding.

Ease of Use: The GUI provides a user-friendly interface, guiding users through the process of uploading images and viewing results.

This Brain Tumor Classification System aims to provide a valuable tool for healthcare professionals in diagnosing brain tumors accurately and promptly. It utilizes machine learning techniques to improve the efficiency of brain tumor detection and classification, ultimately contributing to better patient care.
