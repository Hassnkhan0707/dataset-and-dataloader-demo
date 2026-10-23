# dataset-and-dataloader-demo

## 📌 About the Project
This project demonstrates how to use PyTorch's `Dataset`, `TensorDataset`, and `DataLoader` to prepare and load data for machine learning.

It explains how to organize input features and labels, divide data into batches, and shuffle training data.

## 🛠️ Technologies Used
- Python
- PyTorch
- NumPy
- Google Colab

## 📚 Concepts Covered
- Creating a dataset using `TensorDataset`
- Loading data using `DataLoader`
- Understanding batch size
- Shuffling training data
- Iterating through batches
- Preparing data for neural network training

## 💻 Example

```python
from torch.utils.data import TensorDataset, DataLoader

dataset = TensorDataset(X, y)

loader = DataLoader(
    dataset,
    batch_size=32,
    shuffle=True
)

for batch_X, batch_y in loader:
    print(batch_X.shape)
    print(batch_y.shape)
```

## 🚀 How to Run
1. Open the notebook in Google Colab.
2. Run the cells from top to bottom.
3. Observe how the dataset is divided into batches.

## 🎯 Learning Objective
The goal of this project is to understand how PyTorch prepares and loads data efficiently before training a machine learning model.

## 👨‍💻 Project Type
Beginner-friendly PyTorch learning project.
