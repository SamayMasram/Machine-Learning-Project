🍃 Tea Leaf Disease Classifier
A Deep Learning-based solution to automate the identification of diseases in tea plants. This project uses Convolutional Neural Networks (CNNs) to classify various tea leaf conditions from image data, helping farmers take early action to protect their crops.
___________________________________________________________________________________________________________________________________________________________________
🧐 Problem Statement
Tea is a vital commercial crop, but diseases like Red Rust, Bird's Eye Spot, and Algal Leaf Spot can significantly reduce yield. Manual inspection is slow and error-prone. This project provides a fast, scalable, and accurate way to diagnose these issues using computer vision.
___________________________________________________________________________________________________________________________________________________________________
🛠️ Features
Image Preprocessing: Automated resizing, normalization, and data augmentation to improve model robustness.
Deep Learning Architecture: Utilizes a custom CNN (or Transfer Learning via ResNet/MobileNet) for high-accuracy classification.
Real-world Application: Designed to work with datasets containing thousands of tea leaf images under varying lighting conditions.
___________________________________________________________________________________________________________________________________________________________________
📊 Technical Stack
Language: Python
Libraries: TensorFlow / Keras (or PyTorch), OpenCV, NumPy, Matplotlib
Environment: Google Colab / Asus TUF F15 (NVIDIA GPU Acceleration)
Dataset: Tea Leaf Disease Dataset (sourced via Google Drive)
___________________________________________________________________________________________________________________________________________________________________
🧪 Model Performance
The model was trained on a balanced dataset of healthy and diseased leaves.
Accuracy: [Insert your % here, e.g., 94%]
Optimizer: Adam
Loss Function: Categorical Cross-Entropy
___________________________________________________________________________________________________________________________________________________________________
📂 Project Structure
Plaintext
├── data/               # Dataset (Healthy vs Diseased)
├── notebooks/          # Jupyter notebooks for EDA and Training
├── models/             # Saved .h5 or .tflite model files
├── src/                # Python scripts for inference
└── requirements.txt    # List of dependencies
___________________________________________________________________________________________________________________________________________________________________
🚀 How to Use
Clone the repository:

Bash
git clone https://github.com/YOUR_USERNAME/tea-leaf-classifier.git
Install dependencies:

Bash
pip install -r requirements.txt
Run Inference:
Place an image in the test/ folder and run:

Bash
python predict.py --image test/leaf_sample.jpg
___________________________________________________________________________________________________________________________________________________________________
🛤️ Future Enhancements
[ ] Deploy as a mobile app for on-field diagnostic use.

[ ] Integrate with IoT sensors to monitor humidity and temperature alongside visual data.

[ ] Expand the dataset to include more regional tea varieties.
