# Predicting-User-Exit-for-American-Express-with-ANN
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">    
<h2>Overview</h2>
    <p>This project implements an Artificial Neural Network (ANN) model using TensorFlow and Keras to predict whether a customer will default on their American Express credit card.</p>
    
<h2>Dataset</h2>
    <p>The dataset contains customer details such as demographics, credit history, and transaction data.</p>
    
<h2>Installation</h2>
    <pre><code>pip install numpy pandas tensorflow scikit-learn</code></pre>
    
<h2>Preprocessing</h2>
    <ul>
        <li>Encoding categorical variables (Label Encoding, One-Hot Encoding)</li>
        <li>Splitting data into training and testing sets (80/20)</li>
        <li>Feature scaling using StandardScaler</li>
    </ul>
    
<h2>Model Architecture</h2>
    <ul>
        <li>Input Layer</li>
        <li>Two hidden layers (6 neurons each, ReLU activation)</li>
        <li>Output layer (1 neuron, Sigmoid activation)</li>
    </ul>
    
<h2>Training</h2>
    <p>Compiled using Adam optimizer and binary cross-entropy loss function, trained for 120 epochs with a batch size of 32.</p>
    
<h2>Evaluation</h2>
    <p>Confusion matrix and accuracy score used to assess performance.</p>
    
<h2>Usage</h2>
    <pre><code>git clone https://github.com/Karthikeya-0511/Predicting-User-Exit-for-American-Express-with-ANN.git
cd american-express-ann
python ann_model.py</code></pre>
    
<h2>License</h2>
    <p>This project is licensed under the MIT License.</p>
</body>
</html>
