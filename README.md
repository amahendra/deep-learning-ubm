# 🧠 DSB18: Deep Learning 
**Instructor:** [Amahendra](https://github.com/amahendra)  
*CTO at Centaurops | Author | Lecturer at Bunda Mulia University*

This is an intensive, 28-session engineering-focused course on building, optimizing, and deploying Deep Learning systems. We move from the first principles of Linear Algebra and Calculus to building state-of-the-art architectures using **PyTorch** and **TensorFlow/Keras**.

---

## 📘 Course Comprehensive Description
This course provides a deep-dive into the mechanics of artificial intelligence. Unlike standard courses, we focus on the **"How"** and **"Why"** behind the algorithms.

Students will master:
1.  **Mathematical Rigor:** Solving the Fundamental Spaces, Eigenvalues, and Partial Derivatives that power the learning process.
2.  **Architectural Design:** Moving from the biological neuron to complex Feed-forward and Multi-layered networks.
3.  **The Dual-Framework Approach:** Gaining professional fluency in both **PyTorch** (for low-level control/research) and **TensorFlow/Keras** (for high-level abstraction/production).
4.  **Specialized Domains:** Implementing end-to-end systems for **Computer Vision (CNNs)** and **Sequential/Timeseries Analysis (RNNs)**.

---

## 🗓️ The 28-Session Master Syllabus

### Module I: The Foundations of Intelligence (Sessions 1-6)
* **Sessions 1-2:** The Evolution of Intelligence: From Data Mining to Deep Learning.
* **Sessions 3-4:** The Limits of Traditional Programs vs. The Biological Neuron.
* **Sessions 5-6:** **Advanced Linear Algebra:** Matrix-Vector Multiplication, Column Space, Null Space, and Eigen-Analysis for Optimization.

### Module II: Neural Mechanics & Calculus (Sessions 7-12)
* **Sessions 7-8:** **Feedforward Architectures:** Linear Neurons and Activation Theory (Sigmoid, Tanh, ReLU, Softmax).
* **Sessions 9-10:** **Perceptron Mastery:** Building multi-layered nets and controlling output values.
* **Sessions 11-12:** **The Mathematics of Backpropagation:** Deep dive into Partial Derivatives (Weights/Bias) and Gradient Descent.

### Module III: Mid-Course Integration (Sessions 13-14 + UTS)
* **Sessions 13-14:** Comprehensive Review (Phase I) & Concept Integration.
* **Exam:** **Midterm Evaluation (UTS) - 30%**

### Module IV: Engineering with PyTorch (Sessions 15-18)
* **Sessions 15-16:** **Low-Level Tensors:** Initialization, Attributes, and Complex Tensor Operations.
* **Sessions 17-18:** **Gradients & Autograd:** Using `nn.Module` and building custom Datasets/Dataloaders.

### Module V: Production Systems with Keras & TF (Sessions 19-22)
* **Sessions 19-20:** **TensorFlow/Keras Framework:** Building models from Layers to Inference.
* **Sessions 21-22:** **Training Loops:** Deep dive into Built-in vs. Custom Training/Evaluation Loops.

### Module VI: Applied SOTA Architectures (Sessions 23-28)
* **Sessions 23-24:** **Computer Vision:** CNN Architectures, Convnet training from scratch, and Transfer Learning.
* **Sessions 25-26:** **Timeseries & RNNs:** Sequential modeling and Advanced Recurrent architectures.
* **Sessions 27-28:** **Final System Synthesis:** Review (Phase II) & Project Optimization.
* **Exam:** **Final Evaluation (UAS) - 40%**

---

## 📚 Technical References
The course is built upon three pillars of literature:
* **Primary:** *Fundamentals of Deep Learning, 2nd Ed* (Buduma, Papa | O'Reilly).
* **Conceptual:** *Kecerdasan Buatan dengan Deep Learning* (Pahlevi | Alex Media).
* **Practical:** *Deep Learning with Python, 2nd Ed* (Chollet | Manning).

---

## 🚀 Environment Setup
```bash
# Recommended Environment
conda create -n deep-learning-ubm python=3.10
conda activate deep-learning-ubm
pip install torch torchvision tensorflow keras pandas matplotlib opencv-python
