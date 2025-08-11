# Handwriting-Recognition-with-Tensorflow
Handwriting Recognition with MNIST 📄✏️
This project demonstrates a simple handwriting digit recognition model using the MNIST dataset.
It uses TensorFlow/Keras to train a neural network that classifies handwritten digits from 0–9.

📌 Features
Load and explore MNIST dataset

Visualize handwritten digits

Normalize and preprocess image data

Build a dense neural network using Keras

Train and evaluate model accuracy

Make predictions on test images

🛠️ Technologies Used
Python 3.x

TensorFlow / Keras

Matplotlib

NumPy

📂 Project Structure
bash
Copy
Edit
Handwriting.ipynb   # Jupyter Notebook with full code & explanations
🚀 Getting Started
1️⃣ Clone this repository
bash
Copy
Edit
git clone https://github.com/your-username/handwriting-recognition.git
cd handwriting-recognition
2️⃣ Install dependencies
bash
Copy
Edit
pip install tensorflow matplotlib numpy
3️⃣ Run the notebook
bash
Copy
Edit
jupyter notebook Handwriting.ipynb
📊 Model Overview
Input layer: Flattened 28×28 pixel images (784 features)

Hidden layers: Fully connected dense layers

Activation: ReLU for hidden layers, Softmax for output

Output layer: 10 neurons (digits 0–9)

Loss function: Sparse categorical crossentropy

Optimizer: Adam

📈 Results
Achieves ~97–98% accuracy on test data.

📸 Example Output
Input Digit	Predicted Label
7

📜 License
This project is licensed under the MIT License.
