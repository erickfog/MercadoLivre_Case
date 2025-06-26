# MercadoLivre Case Study

Este repositório contém a solução para dois casos técnicos do MercadoLivre, desenvolvidos como parte do processo de avaliação técnica.

## 📋 Descrição dos Casos

### Case 1: Análise Preditiva de Campanhas de Crédito
- **Objetivo**: Desenvolver um modelo de machine learning para prever a aceitação de campanhas de crédito
- **Dataset**: `MeliDataset.csv` contendo informações sobre clientes, histórico de crédito e campanhas anteriores
- **Tecnologias**: Python, Pandas, Scikit-learn
- **Arquivo**: `notebooks/case_1.ipynb`

### Case 2: Detecção de Orientação de Rosto
- **Objetivo**: Construir um sistema de visão computacional para determinar automaticamente a orientação do rosto em imagens
- **Requisito**: **SEM** utilizar modelos de Machine Learning, apenas técnicas tradicionais de visão computacional
- **Tecnologias**: OpenCV, NumPy
- **Arquivo**: `notebooks/case_2.ipynb`

## 📁 Estrutura do Projeto
MercadoLivre_Case/
├── data/
│ ├── MeliDataset.csv # Dataset para análise preditiva
│ ├── zero.png # Imagem de teste - rosto reto
│ ├── 90.png # Imagem de teste - rosto 90°
│ ├── 180.png # Imagem de teste - rosto 180°
│ └── 270.png # Imagem de teste - rosto 270°
├── notebooks/
│ ├── case_1.ipynb # Análise preditiva de campanhas
│ └── case_2.ipynb # Detecção de orientação de rosto
├── src/ # Código fonte (se aplicável)
├── mind_map.drawio # Diagrama das variáveis
└── README.md # Este arquivo