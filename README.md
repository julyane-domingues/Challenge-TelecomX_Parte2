<h1 align="center">📡 Challenge TelecomX Parte 2</h1>

<p align="center">
  <img loading="lazy" src="https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python"/>
  <img loading="lazy" src="https://img.shields.io/badge/License-Educational-lightgrey?style=for-the-badge"/>
</p>

---

## 📖 Sobre o Projeto

Este projeto foi desenvolvido como parte de um desafio da formação **"Estatisca e MAchine Learning"** da **Alura LATAM** e **Oracle**.  
O objtivo **é desenvolver modelos preditivos** capazes de prever quais clientes têm maior chance de cancelar seus serviços. 

---

## 🎯 Objetivo

- Preparar os dados para a modelagem (tratamento, encoding, normalização).
- Realizar análise de correlação e seleção de variáveis.
- Treinar dois ou mais modelos de classificação.
- Avaliar o desempenho dos modelos com métricas.
- Interpretar os resultados, incluindo a importância das variáveis.
- Criar uma conclusão estratégica apontando os principais fatores que influenciam a evasão.

## 📊 Etapas da Análise

1. **Extração dos dados**: a partir de arquivo tratado na parte do challenge TelecomX.
2. **Transformação dos dados**:
   - Normalização
   - Remoção de colunas irrelevantes.
   - Encoding com Get Dummies: transformação das variáveis categóricas em formato numérico para torná-las compatíveis com algoritmos de machine learning.
   - Balanceamento de classes com SMOTE
3. **Análise de correlação**: Visualização da matriz de correlação para identificar relações entre variáveis numéricas.
4. **Modelagem preditiva**:
   - Separação de dados: divisão do conjunto de dados em treino e teste para avaliar o desempenho do modelo. 
   - Criação de modelos: os modelos utilizados foram a Logistic Regression e o Random Forest.
   - Avaliação dos modelos usando as seguintes métricas: acurácia, precisão, recall, F1-score e matriz de confusão

5. **Resumo geral**: Interpretação e Conclusões.


---

## 🛠️ Tecnologias Utilizadas 

| Categoria | Ferramenta | Função |
|-----------|------------|--------|
| **💻 Linguagem e Ambiente** | **Python** | Linguagem de programação principal |
|  | **Jupyter Notebook** | Ambiente interativo de análise |
| **📊 Manipulação e Análise de Dados** | **Pandas** | Manipulação e análise de dados |
|  | **NumPy** | Operações numéricas e matrizes |
| **📈 Visualização de Dados** | **Matplotlib** | Visualização de dados |
|  | **Seaborn** | Gráficos estatísticos mais sofisticados |
| **⚙️ Pré-processamento** | **scikit-learn - MinMaxScaler** | Normalização de variáveis numéricas para um intervalo específico |
|  | **scikit-learn - StandardScaler** | Padronização de variáveis (média 0, desvio padrão 1) |
|  | **scikit-learn - train_test_split** | Divisão de dados em conjuntos de treino e teste |
|  | **statsmodels - add_constant** | Adição de constante ao conjunto de variáveis para regressões |
|  | **imbalanced-learn - SMOTE** | Balanceamento de classes por oversampling sintético |
| **📐 Análise Estatística** | **statsmodels - variance_inflation_factor** | Cálculo do Fator de Inflação da Variância (VIF) para detecção de multicolinearidade |
| **🤖 Modelagem** | **scikit-learn - LogisticRegression** | Modelo de classificação baseado em regressão logística |
|  | **scikit-learn - RandomForestClassifier** | Modelo de classificação baseado em árvores de decisão em conjunto |
| **🧮 Avaliação de Modelos** | **scikit-learn - accuracy_score** | Métrica de avaliação da acurácia |
|  | **scikit-learn - confusion_matrix** | Matriz de confusão para análise de classificadores |
|  | **scikit-learn - classification_report** | Relatório com métricas como precisão, recall e F1-score |
|  | **scikit-learn - roc_auc_score** | Métrica baseada na área sob a curva ROC |

---

## 📌 Observações

Este projeto foi desenvolvido para **fins exclusivamente educacionais**.  
Os dados apresentados foram fornecidos pela **Alura/Oracle** e **não representam informações reais**.

---

## 📄 Licença

Este projeto é de uso **educacional** e não deve ser utilizado comercialmente.  
Todos os direitos reservados ao autor e à **Alura/Oracle** como formuladores da base educacional.

---

<h2 align="center">👩‍💻 Autora</h2>

<p align="center">
  <b>Julyane Domingues</b> <br>
  Analista de Negócios | Ciência de Dados & Machine Learning <br><br>
  📍 Curitiba - PR, Brasil <br>
  <a href="https://www.linkedin.com/in/seu-linkedin">
    <img src="https://img.shields.io/badge/LinkedIn-blue?logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:seuemail@exemplo.com">
    <img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/seu-github">
    <img src="https://img.shields.io/badge/GitHub-000?logo=github&logoColor=white" />
  </a>
</p>

---
