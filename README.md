# 🔌 Combined Cycle Power Plant (CCPP) – ANN-Based Power Output Prediction

This project uses an **Artificial Neural Network (ANN)** to predict the electrical power output (in megawatts) of a Combined Cycle Power Plant (CCPP) using ambient temperature, pressure, humidity, and vacuum conditions.

## 🧠 Project Objective

To build an **Artificial Neural Network** that can accurately model the non-linear relationship between environmental conditions and power output in a CCPP.

## 🔧 Model Architecture

A simple ANN built with **TensorFlow/Keras**:

- Input Layer: 4 neurons (one for each feature)
- Hidden Layers: 2 hidden layers with ReLU activation
- Output Layer: 1 neuron (for `PE` prediction)
- Loss: Mean Squared Error (MSE)
- Optimizer: Adam

- ## 📦 Tech Stack & Libraries

- Python 3.x
- Pandas, NumPy
- Scikit-learn (for preprocessing)
- TensorFlow / Keras (for ANN)
- Matplotlib, Seaborn (for visualization)

- ## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ccpp-ann.git
   cd ccpp-ann
   
