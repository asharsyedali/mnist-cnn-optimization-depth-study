


# 🧠 MNIST CNN Optimization and Depth Limit Study

This project investigates the impact of learning rate, network depth, activation functions, batch normalization, and batch size on the performance of convolutional neural networks (CNNs) trained on the MNIST handwritten digit classification dataset. The work is conducted as part of an experimental study on deep network optimization strategies.

---

## 📌 Overview

The project explores the following tasks:

1. 🔍 **Optimal Learning Rate Search**  
   Tuning learning rate using SGD + momentum on a shallow CNN.

2. 🧱 **Max Depth without Batch Normalization (Sigmoid Activation)**  
   Exploring limits of Sigmoid-activated CNNs without batch norm or pooling.

3. ⚙️ **Max Depth with BatchNorm + Leaky ReLU**  
   Analyzing how BatchNorm and LeakyReLU support deeper architectures.

4. 📦 **Optimal Batch Size Search**  
   Studying the effect of batch size on generalization performance.

---

## 📊 Results Summary

| ✅ Task                         | 🧪 Key Finding                             |
|-------------------------------|--------------------------------------------|
| Optimal Learning Rate         | **0.05** → Best validation accuracy: **98.62%** |
| Depth w/o BatchNorm           | Unstable beyond **3 layers**               |
| Depth w/ BatchNorm + ReLU     | Best performance at **16–20 layers**       |
| Optimal Batch Size            | **2400 samples** (4%) → **98.47%** test accuracy |

---

## 🧰 Dependencies

Install required libraries:

```bash
pip install -r requirements.txt
````

**Required packages**:

* `torch`
* `torchvision`
* `matplotlib`
* `numpy`

---

## 🚀 How to Run

1. Launch and run: `mnist_cnn_optimization.ipynb`
2. Reproduce each task with included plots and results.
3. Check `project_report.md` for summarized findings.
4. Insert visualizations from `/plots` as needed.

---

## 📄 License

This project is open-source under the MIT License.

---

## 👤 Author

**Syed Mohammad Ali Ashar**
🎓 BS Artificial Intelligence
🏫 University of Management and Technology, Lahore
✉️ [asharshah986@gmail.com](mailto:asharshah986@gmail.com)

```

