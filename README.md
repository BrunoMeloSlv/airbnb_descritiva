# Análise Exploratória de Dados – Airbnb Oslo

Este repositório contém um projeto de Análise Exploratória de Dados (EDA) utilizando Python, com foco em anúncios do Airbnb na cidade de Oslo.
O objetivo é explorar os dados, identificar padrões, analisar preços, correlações entre variáveis e tratar possíveis outliers.

### Objetivos do Projeto

- Realizar limpeza e entendimento inicial dos dados
- Analisar valores ausentes (missing values)
- Explorar a distribuição das variáveis numéricas
- Identificar e analisar outliers
- Avaliar correlações entre variáveis
- Visualizar dados geográficos (latitude e longitude)
- Extrair insights que apoiem tomadas de decisão baseadas em dados

### 🧰 Tecnologias Utilizadas

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly (visualizações interativas)
- GeoPandas / Contextily (visualização espacial, quando aplicável)

📁 Estrutura do Projeto
📦 projeto
 ┣ 📜 projeto1_bruno_melo.ipynb
 ┣ 📜 README.md


### 🔍 Etapas da Análise

1️⃣ Carregamento e inspeção dos dados

- Visualização das primeiras linhas
- Tipos de variáveis
- Dimensão do dataset

2️⃣ Análise de dados ausentes

- Cálculo do percentual de valores nulos por coluna
- Identificação de colunas críticas

3️⃣ Estatística descritiva

- Média, mediana, mínimo e máximo
- Distribuição das variáveis numéricas

4️⃣ Análise de outliers

- Identificação via IQR
- Avaliação do impacto percentual dos outliers
- Discussão sobre remoção vs. tratamento

5️⃣ Correlação entre variáveis

- Cálculo da matriz de correlação
- Visualização via heatmap
- Interpretação das relações mais relevantes

6️⃣ Análise geográfica

- Visualização espacial dos anúncios
- Distribuição de preços por latitude e longitude

### 📈 Exemplos de Análises Realizadas

- Preço médio por bairro (neighbourhood)
- Relação entre disponibilidade e preço
- Impacto do número mínimo de noites no valor da diária
- Concentração geográfica de anúncios mais caros

### 🧠 Principais Aprendizados

- A mediana é mais representativa que a média em datasets com muitos outliers
- Correlação não implica causalidade
- Visualizações espaciais agregam muito valor em análises de imóveis
- Limpeza e entendimento dos dados são etapas essenciais antes de qualquer modelagem

### ▶️ Como Executar o Projeto

Clone este repositório:

git clone https://github.com/BrunoMeloSlv/airbnb_descritiva.git
Instale as dependências:
pip install pandas numpy matplotlib seaborn plotly geopandas contextily
Abra o notebook:
jupyter notebook projeto1_bruno_melo.ipynb

### 🚀 Próximos Passos

- Feature engineering
- Clusterização de bairros
- Modelagem preditiva de preços
- Deploy de visualização interativa (Streamlit)
