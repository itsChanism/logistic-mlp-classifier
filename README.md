# logistic-mlp-classifier

# Logistic & MLP Classifier

This is a simple Python implementation of binary classification using:
- Logistic Regression (Gradient Descent and SGD)
- A one-hidden-layer Multilayer Perceptron (MLP)

## Requirements
- Python 3
- NumPy

## Arguments
	•	<train_file>: Path to a text file with training data (last column = label 0 or 1)
	•	<lr>: Learning rate
	•	<epochs>: Number of training epochs
	•	--method: Training method (gd, sgd, or mlp) [default: gd]
	•	--batch-size: Batch size for SGD or MLP [default: 1]

Example
python main.py data/example.txt 0.1 100 --method mlp --batch-size 10

## Usage

```bash
python main.py <train_file> <lr> <epochs> [--method gd|sgd|mlp] [--batch-size N]

