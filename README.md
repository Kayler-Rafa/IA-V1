# Projeto 2: Machine Learning (IA) - Versão 1

Este repositório contém a primeira parte do Projeto 2 de Machine Learning, desenvolvido por **Rafael Diniz**. O foco desta etapa está na **escolha e pré-processamento dos datasets** dos Grupos A e B, com o objetivo de preparar os dados para tarefas futuras de **classificação, clustering e regressão**.

> ⚠️ **Status do Projeto:** _Em desenvolvimento — esta é apenas a Parte 1 (pré-processamento)._  
> Próximas etapas incluirão: modelagem, avaliação, visualização de resultados e conclusões.

---

## 📂 Estrutura do Projeto

- `projeto2_ml_preprocessamento.ipynb` – Notebook com a implementação da Parte 1
- `README.md` – Este arquivo de documentação

---

## 📊 Datasets Utilizados

### 🅰️ Grupo A: Taiwanese Bankruptcy Prediction  
- Fonte: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/572/taiwanese+bankruptcy+prediction)  
- Tipo: Classificação binária com variáveis financeiras e categóricas

### 🅱️ Grupo B: MiniBooNE Particle Identification  
- Fonte: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/MiniBooNE+particle+identification)  
- Tipo: Classificação binária com dados numéricos de detecção de partículas

---

## ⚙️ Pré-processamento Realizado

### Grupo A
- Remoção de valores ausentes
- Separação entre variáveis (X) e alvo (y)
- Padronização das features com `StandardScaler`
- Visualização da distribuição das variáveis

### Grupo B
- Definição das classes (sinal vs background)
- Padronização com `StandardScaler`
- Visualização por amostragem com boxplots

---

## 📌 Requisitos

Este projeto utiliza as seguintes bibliotecas Python:

pandas, numpy, matplotlib, seaborn  
scikit-learn

Você pode instalar as dependências com:

pip install pandas numpy matplotlib seaborn scikit-learn

---

## 🚧 Próximas Etapas

- Análise exploratória detalhada
- Implementação de algoritmos de classificação e clustering
- Ajuste de hiperparâmetros e avaliação de desempenho
- Relatórios e visualizações finais

---

## ✍️ Autor

**Rafael Diniz**  
Projeto acadêmico – Ciência da Computação  
Faculdade Nova Roma

---

## 📌 Observações

- Os datasets devem ser baixados manualmente e colocados nos caminhos especificados no notebook.
- Este projeto será atualizado à medida que novas partes forem sendo desenvolvidas.
