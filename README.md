# Classificação de Câncer de Pele com Vision Transformer

Projeto de Machine Learning utilizando Vision Transformer (ViT) para classificação de lesões de pele usando o dataset HAM10000.

## 📋 Descrição

Este projeto implementa um modelo de Vision Transformer para classificar diferentes tipos de lesões de pele, auxiliando no diagnóstico precoce de câncer de pele. O dataset HAM10000 contém 10.015 imagens dermatoscópicas de 7 classes diferentes de lesões.

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
├── data/
│   ├── raw/                 # Dados brutos do Kaggle
│   └── processed/           # Dados processados e splits
│
├── notebooks/               # Jupyter notebooks para análise exploratória
│
├── src/                     # Código fonte
│   ├── dataset.py          # Dataset e DataLoaders
│   ├── model.py            # Arquitetura do modelo
│   ├── train.py            # Script de treinamento
│   ├── evaluate.py         # Script de avaliação
│   └── utils.py            # Funções auxiliares
│
├── models/                  # Modelos treinados salvos
│
├── results/                 # Resultados, gráficos e métricas
│
├── requirements.txt        # Dependências Python
└── README.md              # Este arquivo
```

## 🚀 Setup

### 1. Instalar dependências

```bash
pip install -r requirements.txt
```

### 2. Baixar o dataset

1. Acesse: https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000
2. Faça login ou crie uma conta gratuita no Kaggle
3. Clique no botão **Download** para baixar o arquivo ZIP
4. Extraia o conteúdo do ZIP na pasta `data/raw/` do projeto

Após extrair, a estrutura de `data/raw/` deve conter:

```
data/raw/
├── HAM10000_images_part_1/
├── HAM10000_images_part_2/
├── HAM10000_metadata.csv
├── hmnist_8_8_L.csv
├── hmnist_8_8_RGB.csv
├── hmnist_28_28_L.csv
└── hmnist_28_28_RGB.csv
```




