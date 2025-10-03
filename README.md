
[![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SEU_USUARIO/SEU_REPOSITORIO/blob/main/analise_clothing_dataset.ipynb)
![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-orange)
![License](https://img.shields.io/badge/License-Educacional-green)

# 👗 Clothing Co-Parsing Dataset – Análise Completa

Este repositório contém uma análise exploratória e aplicada do **[Clothing Co-Parsing Dataset](https://www.kaggle.com/datasets/balraj98/clothing-coparsing-dataset)**, hospedada em um **Notebook do Google Colab**.  

O objetivo é compreender a estrutura do dataset, visualizar amostras de imagens e explorar como ele pode ser utilizado em tarefas de **classificação, segmentação e reconhecimento de atributos de roupas**.

---

## 📂 Sobre o Dataset
O dataset **Clothing Co-Parsing** contém imagens de roupas com **anotações de segmentação semântica** e **atributos de vestuário**.  
Ele é amplamente utilizado em pesquisas de **visão computacional**, incluindo:
- Reconhecimento de moda 👕👗  
- Segmentação de roupas por peças  
- Análise de atributos (cor, tipo, estilo, etc.)  

---

## 🚀 Como acessar o Notebook

Você pode executar a análise completa diretamente no **Google Colab** sem precisar instalar nada localmente.  

### 👉 Clique no botão abaixo para abrir os Notebooks:

- **Data Cleaning**  
  [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RaphaelCarvalh/clothing-segmentation-project/blob/main/notebooks/01_data_cleaning.ipynb)

- **Training Pipeline**  
  [![Abrir no Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RaphaelCarvalh/clothing-segmentation-project/blob/main/notebooks/02_training_pipeline.ipynb)

---

## 📥 Como carregar o dataset no Colab

1. Acesse o dataset no Kaggle: [Clothing Co-Parsing Dataset](https://www.kaggle.com/datasets/balraj98/clothing-coparsing-dataset)  
2. Gere uma **API Token** no Kaggle (Conta > API > Criar novo token).  
3. No Colab, adicione as keys quando for solicitado para esta sessão.  

### 🔑 Gerando e usando o GitHub Token (para salvar arquivos direto no repositório)

Para enviar arquivos gerados no Colab direto para o repositório GitHub:

1. Acesse o GitHub e vá em **Settings → Developer settings → Personal access tokens → Tokens (classic) → Generate new token**.  
2. Dê um nome ao token (ex: `colab-upload`) e escolha uma expiração (ex: 90 dias ou sem expiração).  
3. Em **Select scopes**, marque **apenas**:  
   - `public_repo` (permite criar e atualizar arquivos em repositórios públicos).  
4. Clique em **Generate token** e copie o token gerado. ⚠️ Ele só aparece uma vez então salve-o!  
5. No Colab, insira o token quando for solicitado de forma segura:
