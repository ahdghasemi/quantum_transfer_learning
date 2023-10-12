# Project Origin
This is a revised and modified version of the "quantum_transfer_learning" project from Xanadu, which can be found at the following URL: https://github.com/XanaduAI/quantum-transfer-learning/blob/master/c2q_transfer_learning_cifar.ipynb. We have made several modifications to the original code, including:

* Changing the binary classification task to a multi-class classification task
* Writing our own PyTorch version of the train and validate modules, which are more organized and easier to understand

# Getting Started
To get started with this project, clone the repository and install the required dependencies. You can do this by running the following commands:

git clone https://github.com/username/QuantumTransferLearning.git
cd QuantumTransferLearning
pip install -r requirements.txt

Replace "username" with your GitHub username.

# Running the Code
To train and evaluate the model on the CIFAR10 dataset, run the following command:

python train.py

This will train the model and print out the validation accuracy.

# Contributing
We welcome contributions to this project! To contribute, fork the repository and create a new branch for your changes. When you're ready to submit your changes, create a pull request against the main branch. Please include a detailed description of your changes in the pull request.

# License
This project is licensed under the MIT License. See the LICENSE file for more information.
