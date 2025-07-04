# 🏠 Apartment Price Prediction with Feature Scaling

This project applies **multiple linear regression** to predict apartment prices using two features: `size` (in square meters) and `year` (year of construction). The exercise emphasizes the importance of **feature scaling** and introduces model evaluation through **R² and Adjusted R²**.

---

## 📌 Objectives

- Understand how different scales between features (e.g., size vs. year) affect model performance.
- Compare a **simple linear regression model** (only `size`) with a **multiple regression model** (`size + year`).
- Evaluate whether the additional feature improves the model using **R²** and **Adjusted R²**.

---

## 📊 Key Results

- **Simple Linear Regression (size only)**  
  - R²: `0.7447`

- **Multiple Linear Regression (size + year)**  
  - R²: `0.7765`  
  - Adjusted R²: `0.7719`

> ✅ The increase in Adjusted R² suggests that `year` improves the model after accounting for complexity.

---

## ⚙️ Tools Used

- Python  
- `scikit-learn` (LinearRegression, StandardScaler)  
- Jupyter Notebook  
- pandas & numpy

---

## 🌍 Languages

- 📘 Notebook in English  
- 📌 GitHub description in **English & Portuguese**

---

## 🧠 What I Learned

- How to apply **standardization (Z-score normalization)** to bring variables to the same scale.
- How to **interpret Adjusted R²** to decide if a new feature truly adds value.
- That even a small increase in Adjusted R² can justify adding a variable, as long as it aligns with real-world logic.

---

## 📂 Folder/File

- `sklearn - Feature Scaling Exercise.ipynb`: Full notebook with code, outputs, and analysis.

---

## 📎 Related Concepts

- Feature Scaling  
- Linear Regression  
- Adjusted R²  
- Model Evaluation  
- scikit-learn

---

# 🏠 Previsão de Preços de Apartamentos com Normalização de Variáveis

Este projeto aplica **regressão linear múltipla** para prever preços de apartamentos utilizando duas variáveis: `tamanho` (em metros quadrados) e `ano` (ano de construção). O exercício enfatiza a importância da **normalização de variáveis (feature scaling)** e introduz a avaliação de modelos por meio de **R² e R² ajustado**.

---

## 📌 Objetivos

- Compreender como diferentes escalas entre variáveis (ex: tamanho vs. ano) afetam a performance do modelo.  
- Comparar um **modelo de regressão linear simples** (somente `tamanho`) com um **modelo de regressão múltipla** (`tamanho + ano`).  
- Avaliar se a variável adicional melhora o modelo usando **R²** e **R² ajustado**.

---

## 📊 Resultados Principais

- **Regressão Linear Simples (apenas tamanho)**  
  - R²: `0.7447`

- **Regressão Linear Múltipla (tamanho + ano)**  
  - R²: `0.7765`  
  - R² ajustado: `0.7719`

> ✅ O aumento no R² ajustado sugere que `ano` melhora o modelo mesmo após o ajuste pela complexidade.

---

## ⚙️ Ferramentas Utilizadas

- Python  
- `scikit-learn` (LinearRegression, StandardScaler)  
- Jupyter Notebook  
- pandas & numpy

---

## 🌍 Idiomas

- 📘 Notebook em inglês  
- 📌 Descrição no GitHub em **português e inglês**

---

## 🧠 O que Aprendi

- Como aplicar a **padronização (normalização Z-score)** para trazer variáveis à mesma escala.  
- Como **interpretar o R² ajustado** para decidir se uma nova variável realmente adiciona valor.  
- Que mesmo um pequeno aumento no R² ajustado pode justificar a adição de uma variável, desde que faça sentido no mundo real.

---

## 📂 Arquivo

- `sklearn - Feature Scaling Exercise.ipynb`: Notebook completo com código, saídas e análise.

---

## 📎 Conceitos Relacionados

- Normalização de Variáveis (Feature Scaling)  
- Regressão Linear  
- R² Ajustado  
- Avaliação de Modelos  
- scikit-learn

---

