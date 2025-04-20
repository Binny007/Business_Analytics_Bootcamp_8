# Business_Analytics_Bootcamp_8


#Gaussian Mixture Model



# 🎯 Gaussian Mixture Model Clustering for Customer Segmentation

Welcome to the world of **unsupervised learning**!\
This project dives deep into **Gaussian Mixture Models (GMM)** — a powerful, probabilistic clustering technique used to **discover hidden patterns** in customer behavior.

## 📂 Repository Overview

This project explores clustering and customer segmentation using the **Gaussian Mixture Model**, enriched with tools like **AIC** and **BIC** for model selection.

| File                                  | Description                                 |
| ------------------------------------- | ------------------------------------------- |
| `Gaussian Mixture Model.ipynb`        | Python notebook implementing GMM clustering |
| `CreditCard.csv`                      | Raw dataset used for analysis               |
| `R_ Expenditure and Default Data.pdf` | Description of dataset variables            |

---

## 🧠 What You'll Learn

### 📌 1. Clustering (Unsupervised Learning)

Clustering is about **grouping similar data points** together. It’s one of the core unsupervised machine learning techniques used in segmentation, anomaly detection, and more.

In this project, we use GMM to group credit card users based on their behavior and spending habits.

### 📌 2. Gaussian Mixture Model (GMM)

Unlike hard clustering methods (e.g., K-Means), **GMM assigns probabilities** to each data point for belonging to a cluster. This is helpful in real-world situations where boundaries between groups are not distinct.

Each cluster in GMM is modeled as a **Gaussian (normal) distribution**, and the model learns how many Gaussians best describe your dataset.

### 📌 3. Choosing the Optimal Number of Clusters (AIC & BIC)

Two major challenges in clustering:

- ❓ How many clusters should I choose?
- 🤔 Is my model too simple or too complex?

That’s where **AIC (Akaike Information Criterion)** and **BIC (Bayesian Information Criterion)** come in.

#### ✴ Akaike Information Criterion (AIC)

- Measures how well a model fits the data while penalizing for too many parameters.
- Lower AIC = better model balance (fit vs. complexity).

#### ✴ Bayesian Information Criterion (BIC)

- Similar to AIC but adds a **stronger penalty** for complexity.
- Often more conservative in selecting simpler models.

We compare AIC and BIC across multiple models to pick the best `n_clusters`.

---

## 📊 Project Summary

✔️ **Dataset**: Credit card behavior of customers\
✔️ **Goal**: Group customers based on spending & activity\
✔️ **Techniques**: Gaussian Mixture Model, AIC/BIC scoring\
✔️ **Insights**: Labeled customer groups like:

- 🧑‍💼 *Lower Middle Class*
- 💤 *Inactive*
- 💳 *High Rollers*
- 🧠 *Conscious High Income*
- 💼 *Upper Middle Class*
- 🛍️ *Active Purchasers*

These segments can help businesses:

- Identify valuable customers
- Design tailored marketing campaigns
- Understand spending behavior

---

## 🛠 Libraries Used

- `NumPy`
- `Pandas`
- `Matplotlib`
- `sklearn.mixture.GaussianMixture`

---

## 📸 Visual Output

📉 **AIC vs BIC Curve** – helps choose the optimal number of clusters\
📦 **Cluster Assignments** – each customer tagged to a segment\
📊 **Cluster Means** – interpretable statistics per group

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Binny007/Business_Analytics_Bootcamp_8.git
   ```
