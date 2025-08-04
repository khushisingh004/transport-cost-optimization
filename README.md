Project Description 
This project solves a real-world transportation cost optimization problem using Linear Programming and the Python library PuLP. It finds the most cost-effective way to ship goods from multiple warehouses to retail stores while meeting supply and demand constraints.
# Transport Cost Optimization Using Linear Programming 🚛📦

This project solves a business logistics problem: minimizing the transportation cost from multiple warehouses to retail stores using **Linear Programming (LP)** with the Python library **PuLP**.

---

## 📌 Problem Statement

A company has:
- 2 warehouses with limited supply
- 3 stores with specific demand
- A table of transportation costs per unit between warehouses and stores

The goal is to **minimize total transport cost** while meeting all supply and demand requirements.

---

## 🛠️ Technologies Used

- Python 🐍
- PuLP (LP Solver)
- Google Colab / Jupyter Notebook

---

## 🧮 Optimization Model

- **Decision Variables**: How many units to send from each warehouse to each store
- **Objective Function**: Minimize total cost
- **Constraints**:
  - Supply limit per warehouse
  - Demand requirement per store
  - All values ≥ 0

---

## 📊 Output Example

W1_S1 = 20.0
W1_S2 = 50.0
W2_S1 = 20.0
W2_S3 = 30.0
Total Transportation Cost: ₹310.0


---

## ✅ Results

The model provides a cost-optimal plan satisfying all constraints. A great beginner-friendly example of applying data science and operations research in real-world business scenarios.

---

## 📁 File

- `Transport_Optimization.ipynb`: Main notebook with code, output, and explanation.

---

## 📣 Author

👩‍💻 Khushi – Data Science Intern at CodTech  
Feel free to fork and explore!
