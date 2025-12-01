# Classificação de Câncer de Pele

Projeto de Machine Learning para classificação de lesões de pele usando o dataset HAM10000.

## 📋 Descrição

Este projeto tenta implementar diferentes métodos como Redes Neurais Convolucionais (CNNs) e Vision Transformers para classificar diferentes tipos de lesões de pele, auxiliando no diagnóstico precoce de câncer de pele. O dataset HAM10000 contém 10.015 imagens dermatoscópicas de 7 classes diferentes de lesões.

## 🎯 Classes do Dataset

1. **Melanoma (mel)** - Melanoma maligno
2. **Melanocytic nevi (nv)** - Nevos melanocíticos benignos
3. **Basal cell carcinoma (bcc)** - Carcinoma basocelular
4. **Actinic keratoses (akiec)** - Queratose actínica / Carcinoma in situ
5. **Benign keratosis (bkl)** - Queratose benigna
6. **Dermatofibroma (df)** - Dermatofibroma
7. **Vascular lesions (vasc)** - Lesões vasculares

## 🗂️ Estrutura do Projeto

```
SkinCancer_VisionTransformer_Project/
│
├── data/                                # Dataset Utilizado
│
├── SkinCancerProject.ipynb              # Jupyter Notebook do Projeto
│
├── models/                              # Modelos treinados salvos
│
├── requirements.txt                     # Dependências Python
│
└── README.md                            # Este arquivo
```

## 🚀 Setup

### 1. Instalar dependências

```bash
pip install -r requirements.txt
```

### 2. Instalar o token do kaggle

- Instale o arquivo [`kaggle.json`](https://www.kaggle.com/settings). Para baixá-lo, acesse o link e role até a parte de Legacy API Credentials, onde você encontrará o botão "Create Legacy API Key". Basta fazer o download do arquivo e colocá-lo na raiz do projeto.

```json
{
  "username": "example",
  "key": "123456789"
}
```
