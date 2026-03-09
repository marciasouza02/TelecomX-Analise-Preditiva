
<h1 align="center">:bar_chart: TelecomX - Prevendo evasão de clientes</h1>

## 📌**Contexto do Projeto:**

Desenvolver modelos preditivos capazes de prever quais clientes têm maior chance de 
cancelar seus serviços e identificar os principais fatores que influenciam a evasão de clientes (Churn) na empresa
de telecomunicação Telecom X

A empresa quer antecipar o problema da evasão, e foi solicitado a construção de um pipeline robusto para essa etapa, a partir
da análise exploratória e da aplicação de modelos de Machine Learning, buscou-se compreender quais características 
dos clientes aumentam a probabilidade de cancelamento do serviço e propor estratégias de retenção baseadas em dados.

Foi desenvolvido modelos preditivos capazes de prever quais clientes têm maior chance de cancelar seus serviços e a 
partir disso e antecipar o problema da evasão.

----

## 🎯**Objetivo:**

- Preparar os dados para a modelagem (tratamento, encoding, normalização).

- Realizar análise de correlação e seleção de variáveis.

- Treinar dois ou mais modelos de classificação.

- Avaliar o desempenho dos modelos com métricas.

- Interpretar os resultados, incluindo a importância das variáveis.

- Criar uma conclusão estratégica apontando os principais fatores que influenciam a evasão.

----
 
## 🔍 Etapas do Projeto:

### 1 - Importação dos Dados

- Carregamento da base de dados do arquivos da empresa utilizando a biblioteca pandas

---

### 2 - Limpeza e Tratamento dos Dados

- Ajuste de tipos de dados 

- Identificação e tratamento de valores ausentes, vazios incluindo a variável alvo Churn

-  Verificação de valores únicos em cada variável

- Conversão de variáveis categóricas utilizando One-Hot Encoding

- Exclusão de variáveis que não eram relevantes para o modelo, que não apresentaram associação significativa

- Exclusão das variáveis devido multicolinearidade

- Transformação das colunas categoricas em numericas

- Separação entre variáveis explicativas (X) e variável alvo (Churn)

- Divisão da base em treino e teste

- Balanceamento da classe utilizando RandomOverSampler, devido ao desbalanceamento entre clientes que cancelaram e os que permaneceram

- Normalização dos dados

- Verificação de importancia das variaveis

- Treinamento dos modelos Random Forest e Regressão Logistica

---

### 3 - Avaliação do impacto dos serviços contratados

- Análises de correlação entre variáveis

---

### 4 - Construção de gráficos para identificação de padrões

- Graficos de barras, setores,heatmap

---

### 5 - Modelos para o treinamento

#### Random Forest
O segundo modelo utilizado foi o Random Forest, um algoritmo baseado em múltiplas 
árvores de decisão que melhora a capacidade de generalização e reduz o risco de overfitting.

#### Regressão Logistica
Esse modelo permitiu identificar a importância relativa das variáveis, mostrando quais fatores mais influenciam na 
previsão de cancelamento. A Regressão Logística é um modelo estatístico amplamente utilizado em problemas de 
classificação binária. Neste estudo, ela foi aplicada para estimar a probabilidade de um cliente cancelar o serviço.

### 5.1 Comparação do Desempenho dos Modelos

Os modelos foram avaliados utilizando as seguintes métricas:

- Acurácia – proporção de previsões corretas

- Precisão – proporção de previsões positivas corretas

- Recall – capacidade do modelo identificar clientes que realmente cancelam

- F1-score – equilíbrio entre precisão e recall

### 5.2 - Conclusão dos Modelos - Resultados Observados

A Regressão Logística apresentou boa interpretabilidade e permitiu entender o impacto das variáveis.

O Random Forest apresentou melhor capacidade de capturar relações não lineares e identificar variáveis mais 
relevantes.

Em geral, o Random Forest tende a apresentar melhor desempenho preditivo, enquanto a Regressão Logística oferece 
maior interpretabilidade.


Com base nas métricas analisadas, o modelo de Regressão Logística mostrou-se mais adequado para o problema de 
previsão de evasão de clientes, pois apresenta melhor desempenho na identificação de clientes com maior probabilidade de cancelamento. Esse resultado é relevante para estratégias de retenção, permitindo que a empresa identifique e atue 
preventivamente sobre clientes com risco de evasão

---

## 6 -🛠️ Ferramentas e Tecnologias

- 🐍 **Python** – linguagem principal para análise de dados
- 🐼 **Pandas** – manipulação, limpeza e tratamento de dados
- 🐼 **Scipy** - resolver problemas complexos de matemática
- 🐼 **SKlean** - aplicação prática dessa matemática para prever o futuro ou encontrar padrões ocultos
- 🔢 **NumPy** – operações matemáticas e computação numérica
- 📊 **Matplotlib** – visualização de dados
- 📓 **Jupyter Notebook** – desenvolvimento e documentação das análises
- ☁️ **Google Colab** – ambiente de desenvolvimento em nuvem
- ⚙️ **ETL** – extração, transformação e carga de dados
- 📂 **Git & GitHub** – versionamento de código e portfólio

----

## 👩‍💻 Autora

Clea Marcia

Analista de Dados | Ciência de Dados

Projeto desenvolvido para fins de estudo (Alura One) e portfólio profissional.


