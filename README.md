# CPU-Thermal-Simulation-with-RC-Network-and-DVFS-Control

This project simulates the thermal behavior of a CPU using an RC thermal network model, incorporating both dynamic and leakage power. It compares three control strategies:

-  **Free-running** (no control)
-  **Threshold-based DVFS**
-  **PID-controlled DVFS**

The goal is to evaluate thermal regulation, power efficiency, and stability under a synthetic workload.

---

## 📂 Project Structure

- `Thermal_modeling.ipynb`: Full simulation code (Python notebook)
- `report.pdf`: Detailed LaTeX report
- `README.md`: This file

---

## 📊 Key Results

| Strategy         | Max Temp (°C) | Energy (J) | EDP   | Overshoot |
|------------------|---------------|------------|-------|------------|
| Free-running     | 180.6         | 11.99      | 119.91| 97.61 °C   |
| Threshold DVFS   | 85.0          | 4.72       | 47.22 | 2.03 °C    |
| PID DVFS         | 81.6          | 4.58       | 45.81 | **0.00 °C**|

- PID reduces peak temperature by **99°C**
- PID is **3.0% more energy-efficient** than threshold DVFS
- PID eliminates overshoot and maintains smoother control

---


## 🛠️ Technologies

- Python 3 (NumPy, Matplotlib, Pandas)
- LaTeX for report formatting
- Git/GitHub for version control

---

## 📬 Contact

Mohammed Amine ZNIYED  
🧠 Thermal Modeling Engineer Candidate  
📧 [your.email@example.com]  
🔗 [LinkedIn](https://www.linkedin.com/in/amine-zniyed-1154ba190/)
