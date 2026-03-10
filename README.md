# 🌱 PlantDiseaseML — Classificação de Doenças em Plantas Usando Visão Computacional

Este repositório apresenta um sistema de **visão computacional baseado em Deep Learning** para **detecção automática de doenças em plantas**.  
O projeto utiliza técnicas modernas de aprendizado profundo para classificar folhas entre diferentes tipos de doenças ou saudáveis.

---

## 🎯 Objetivo do Projeto

Desenvolver um modelo de IA capaz de:
- Detectar doenças em plantas a partir de imagens
- Auxiliar agricultores e pesquisadores
- Automatizar o diagnóstico de saúde vegetal
- Reduzir perdas de produção e melhorar eficiência agrícola

---

## 🧠 Tecnologias Utilizadas

- **Python 3.10+**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy & Pandas**
- **Matplotlib / Seaborn**
- **Google Colab (opcional)**

---

## 🖼 Dataset

O projeto utiliza um dataset contendo imagens de folhas com:
- Manchas  
- Fungos  
- Deficiências nutricionais  
- Folhas saudáveis  

As imagens passam por:
- Redimensionamento  
- Padronização  
- Normalização  
- Aumento de dados (*data augmentation*)

---

## 🏗 Arquitetura do Modelo

O modelo final usa:
- **CNN (Convolutional Neural Network)**  
- Camadas Conv2D + MaxPooling  
- Dropout para evitar overfitting  
- Otimizador Adam  
- Métrica Accuracy  

Também foram feitos experimentos com:
- Aumento de dados (augmentation)  
- Transfer Learning (ex.: MobileNetV2)

---

## 📊 Resultados Obtidos

- Acurácia média: **85%–95%** (dependendo da arquitetura)
- Boa generalização com dataset equilibrado
- Matriz de confusão incluída no notebook

---

## ▶️ Como executar

```bash
pip install -r requirements.txt
python train.py
