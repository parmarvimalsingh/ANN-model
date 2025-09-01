# Syngas Composition Prediction with ANN  
### 🔬 Biomass Gasification Meets Machine Learning  

This project explores how **Artificial Neural Networks (ANNs)** can be used to predict the **syngas composition** resulting from biomass gasification. The motivation was to move beyond purely empirical correlations and instead use a data-driven approach that captures nonlinear relationships between biomass properties, operating conditions, and gas yields.  

The work is built entirely in **MATLAB**, focusing on **symbolic modeling, training, and testing** of feedforward neural networks. The emphasis is on interpretability and performance — tuning parameters carefully rather than treating the ANN as a black box.  

---

## 🧠 What’s Inside  

### Core Data & Model  
- **Dataset (353 points)** — Compiled from reference papers, covering a wide range of feedstock and operating parameters  
- **Inputs (7 parameters)** — Biomass composition & process conditions (temperature, pressure, etc.)  
- **Outputs** — Predicted syngas composition (H₂, CO, CO₂, CH₄ fractions)  

### Network Design  
- **Two-layer feedforward ANN** built in MATLAB  
- **Training algorithm** — Levenberg–Marquardt (LM), chosen for its speed and accuracy  
- **Training strategy** — Multiple epochs with convergence monitoring to ensure stability  

---

## 📌 Highlights  
- How a **two-layer ANN** can approximate nonlinear gasification correlations  
- Why the **Levenberg–Marquardt algorithm** provides faster convergence than standard gradient descent  
- How increasing dataset diversity (500 points, 7 inputs) boosts **generalization**  
- Demonstrated that ANN can achieve **high-fidelity predictions** compared to experimental results  

---

## 🎯 Who This Is For  
- Students/researchers working on **biomass gasification modeling**  
- Engineers exploring **AI in renewable energy systems**  
- Anyone curious about applying **ANNs in MATLAB** for scientific problems  

---

## 🛠 Tools Used  
- **MATLAB** — for ANN training, validation, and visualization  
- **Neural Network Toolbox** — LM algorithm implementation and model tuning  

---

## 📬 Contact  
If you’re working on biomass modeling or machine learning for energy systems, let’s connect:  

📧 vimals24@iitk.ac.in  

---

