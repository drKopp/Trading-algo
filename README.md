# 📊 Analyse Financière et Prédiction des Prix des Actions avec Python

Ce dépôt contient une série de notebooks Jupyter explorant différentes techniques d’analyse de données financières, de feature engineering, de modélisation et de backtesting vectorisé d’une stratégie de trading.

---

## 🗂️ Fichiers du projet

### 📘 `01_Features_Engineering.ipynb`
> 🔧 **Objectif** : extraction de caractéristiques à partir des données historiques

- Calculs de :
  - **SMA** (Moyenne mobile simple)
  - **MSD** (Écart-type mobile)
  - **TA** (Indicateurs techniques personnalisés)
- Création de **fonctions réutilisables** pour l’ingénierie des variables

---

### 📘 `02_Linear_Regression_to_predict_stock_prices.ipynb`
> 📈 **Objectif** : modéliser les prix d’actions avec une approche supervisée

- Régression polynomiale pour prévoir l’évolution des prix
- Comparaison entre différents degrés de polynôme
- Visualisations des résultats et erreurs de prédiction

---

### 📘 `03_Vectorized_Backtesting.ipynb`
> 💹 **Objectif** : évaluer les performances d’une stratégie de trading

- Implémentation vectorisée pour simuler des portefeuilles
- Calculs de métriques :
  - **Sortino Ratio**
  - **Beta / Alpha**
  - **Drawdown** et **Max Drawdown**
- Création de **fonctions de backtest** réutilisables pour d’autres stratégies

---

## ⚙️ Technologies utilisées

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---
