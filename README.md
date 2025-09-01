# AxiomML

**Building Machine Learning & Deep Learning from First Principles.**

AxiomML is an educational, from-scratch implementation of fundamental machine learning algorithms. The goal is to demystify the "black box" nature of libraries like Scikit-learn and PyTorch by providing clean, well-documented, and simple code for the core components of ML.

> **An axiom is a statement that is taken to be true, to serve as a premise or starting point for further reasoning and arguments.**
> This library is our starting point.

## 🧠 Philosophy

Modern ML libraries are powerful but abstract. They hide the beautiful math and logic underneath layers of optimization and API design. **AxiomML strips that away.** Each algorithm is built from the ground up using only NumPy and core Python, prioritizing clarity and educational value over performance and features.

## 📚 Implemented Algorithms (The Axioms)

*This is a living project. The list will grow.*

### 🔹 Phase 1: The Absolute Fundamentals (Current Focus)
- [ ] **Linear Regression** (OLS & Gradient Descent)
- [ ] **Logistic Regression**
- [ ] `StandardScaler`, `MinMaxScaler`
- [ ] Metrics: `MSE`, `R2-Score`, `Accuracy`

### 🔹 Phase 2: Core Models & Concepts (Planned)
- Decision Trees (CART)
- Random Forests (Bagging)
- K-Nearest Neighbors (KNN)
- Naive Bayes
- K-Means Clustering
- Principal Component Analysis (PCA)

### 🔹 Phase 3: Neural Foundations (Future)
- Feedforward Neural Networks (Backpropagation)
- Convolutional Neural Networks (CNNs)
- Recurrent Neural Networks (RNNs / LSTMs)

## 🚀 Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/a-jacked-nerd/AxiomML.git
    cd AxiomML
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Import and use!** The goal is to mirror the Scikit-learn API for familiarity.
    ```python
    from axiom.linear_model import LinearRegression
    from axiom.preprocessing import StandardScaler

    # ... Your code here ...
    model = LinearRegression()
    model.fit(X, y)
    predictions = model.predict(X_test)
    ```

## 🤝 Contributing

This is primarily a personal educational journey, but discussions, suggestions, and contributions are welcome! Feel free to open an issue to discuss a new algorithm or submit a pull request.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
