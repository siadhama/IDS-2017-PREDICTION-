
# Intrusion Detection in Network Traffic using Machine Learning

** CIC IDS 2017 |MINOR PROJECT- Punjab Engineering College, Chandigarh**

> An ML-based Intrusion Detection System leveraging the **Whale Optimization Algorithm (WOA)** for intelligent feature selection and high-accuracy attack detection.

---

##  Overview

This project builds a **Machine Learning–driven Intrusion Detection System (IDS)** using the **CIC IDS 2017 dataset**.
We tackle major challenges in IDS — *redundant features, data imbalance, and poor generalization* — by integrating **WOA** with ML models such as **Random Forest**, **XGBoost**, and **Neural Networks** to achieve robust network attack detection.

---

##  Approach

1. **Data Preprocessing:** Cleaned, normalized, and balanced the CIC IDS 2017 dataset.
2. **Feature Selection:** Applied Whale Optimization Algorithm (WOA) to identify the most relevant attributes.
3. **Model Training:**
   * Binary classification (Attack vs. Benign) → **XGBoost**
   * Multiclass classification → **Neural Network**
4. **Evaluation:** Compared accuracy, precision, and execution time across models.

---

##  Tech Stack

* **Languages:** Python
* **Libraries:** Scikit-learn, Pandas, NumPy, Matplotlib, TensorFlow, XGBoost
* **Optimization:** Whale Optimization Algorithm (WOA)
* **Dataset:** [CIC IDS 2017](https://www.unb.ca/cic/datasets/ids-2017.html)

---

##  Future Scope

* Extend to **CIC IDS 2018/2023** datasets.
* Add **real-time detection pipeline** and dashboard.

---

##  Team

| Name             | Roll No. |
| ---------------- | -------- |
| **Sia Dhama**    | 23103009 |
| **Rivea Bansal** | 23103079 |
| **Namita**       | 23103105 |
| **Aniket Harit** | 23103127 |

**Supervisor:** Prof. *Mayank Gupta*
**Department:** Computer Science and Engineering, PEC Chandigarh

---

##  References

* Gupta & Rani (2023), *ML-based IDS using Infinite Feature Selection and WOA*, AIP Conf. Proc.
* [CICIDS2017 Dataset Docs](https://www.unb.ca/cic/datasets/ids-2017.html)

---
