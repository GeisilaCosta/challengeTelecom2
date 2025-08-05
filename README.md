# challengeTelecom2
# 📊 Telecom X – Parte 2: Prevendo Churn

## 📘 Sobre o Projeto

Este projeto é a **segunda parte** do desafio proposto pela **Telecom X**, com foco em prever a **evasão de clientes (churn)** por meio de **modelos de Machine Learning**.  
Após uma análise exploratória bem-sucedida, o objetivo agora é **antecipar quais clientes estão propensos a cancelar os serviços**, desenvolvendo **modelos de classificação robustos e interpretáveis**.

---

## 🎯 Objetivos

- 🔄 Realizar o pré-processamento dos dados (tratamento de nulos, encoding, normalização).
- 🧠 Treinar **dois ou mais modelos de classificação**.
- 📈 Avaliar os modelos com métricas apropriadas.
- 🧩 Interpretar os resultados, com foco na **importância das variáveis**.
- 📌 Gerar **conclusões estratégicas** sobre os principais fatores que influenciam o churn.

---

## 🧰 Tecnologias e Bibliotecas

- `Python`
- `Pandas`, `NumPy`
- `Matplotlib`, `Seaborn`, `Plotly`
- `Scikit-learn`
- `XGBoost` (opcional)
- `Joblib` (para salvar modelos)

---

## 🧪 Etapas do Projeto

### 1. **Importação e pré-processamento dos dados**
- Remoção de dados inconsistentes e nulos
- Codificação de variáveis categóricas (One-Hot ou Label Encoding)
- Normalização de variáveis numéricas (MinMaxScaler ou StandardScaler)

### 2. **Análise de Correlação**
- Uso do `.corr()` do Pandas
- Matriz de correlação e mapa de calor com Seaborn
- Seleção de features mais relevantes

### 3. **Modelagem Preditiva**
- Separação entre dados de treino e teste
- Treinamento de ao menos dois modelos:
  - Ex: `Random Forest`, `Logistic Regression`, `Decision Tree`, `XGBoost`
- Comparação dos modelos com base em:
  - Acurácia
  - Precision
  - Recall
  - F1-Score
  - Matriz de Confusão

### 4. **Interpretação dos Resultados**
- Avaliação dos erros e acertos de cada modelo
- Visualização da **importância das variáveis**
- Discussão sobre os fatores que mais influenciam a evasão de clientes

### 5. **Conclusão Estratégica**
- Pontos-chave extraídos da modelagem
- Sugestões de ações para reduzir o churn com base nos insights


## 🧠 Possíveis Modelos Utilizados

- `RandomForestClassifier`
- `LogisticRegression`
- `DecisionTreeClassifier`
- `XGBClassifier`
- `KNeighborsClassifier`

---

## 📊 Resultados Esperados

- Modelos com bom **recall** (para detectar clientes que vão sair)
- Insights claros sobre **perfil dos clientes com maior propensão à evasão**
- Entrega de um **modelo salvo** para uso futuro (via `joblib`)

---

## ✅ Conclusão

Com esta entrega, foi possível prever a evasão de clientes da Telecom X com base em dados históricos, utilizando técnicas de Machine Learning supervisionado.  
A análise também permitiu identificar **variáveis-chave** para ações estratégicas, como:

- A **conta mensal elevada**
- **Falta de múltiplos serviços contratados**
- Clientes com **curto tempo de permanência**

Esses insights abrem caminho para **intervenções proativas** da empresa visando a **retenção de clientes** e a **redução da taxa de churn**.
