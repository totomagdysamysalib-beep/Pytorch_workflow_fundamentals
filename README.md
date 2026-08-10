# 🚀 PyTorch Workflow Fundamentals

Welcome to my repository! This project serves as a foundational milestone in my Deep Learning journey, where I implemented a complete **End-to-End PyTorch Workflow** from scratch.

---

## 📌 Project Overview
The goal of this project is to build and understand the core components of training and evaluating a machine learning model using **PyTorch**. 

Using a synthetic linear dataset, the project covers the full lifecycle of a deep learning task—from data preparation to saving the trained model.

---

## 🔑 Key Features & Concepts Covered
* **Data Preparation**: Generated synthetic linear data and split it into training ($80\%$) and testing ($20\%$) sets.
* **Model Architecture**: Built a custom Linear Regression model by subclassing `nn.Module`.
* **Loss Function & Optimizer**: 
  * Loss Function: Mean Absolute Error (`nn.L1Loss()`)
  * Optimizer: Stochastic Gradient Descent (`torch.optim.SGD`)
* **Training Loop**: Implemented forward pass, loss calculation, backpropagation (`loss.backward()`), and optimizer step (`optimizer.step()`).
* **Evaluation & Inference**: Evaluated model performance using `torch.inference_mode()`.
* **Model Persistence**: Saved and reloaded the model's parameters using `state_dict()`.

---

## 🛠️ Tech Stack
* **Language**: Python 3
* **Framework**: PyTorch
* **Libraries**: Matplotlib, NumPy

---

## 📈 Learnings & Takeaways
> "Mastering the fundamentals is the most critical step toward building complex AI architectures."

This hands-on exercise reinforced my understanding of PyTorch tensors, gradient computation, dynamic computation graphs, and explicit control over the training pipeline.

---
*Created with passion to document my growth in Artificial Intelligence & Deep Learning!* 💡
