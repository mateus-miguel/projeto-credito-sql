# 📊 Análise Exploratória de Dados de Crédito

## 📌 Descrição do Projeto

Este projeto realiza uma **análise exploratória de dados (EDA)** sobre um conjunto de dados de **clientes de crédito**, contendo informações demográficas, financeiras e comportamentais, como idade, sexo, escolaridade, renda, tipo de cartão, limite de crédito e histórico de transações.

O objetivo principal é **entender o perfil dos clientes**, identificar padrões associados ao **default (inadimplência)** e extrair insights que possam apoiar **tomadas de decisão em contextos financeiros**, como concessão de crédito e análise de risco.

---

## 🗂️ Conjunto de Dados

O dataset está em formato CSV e contém, entre outras, as seguintes variáveis:

- **Demográficas**: idade, sexo, estado civil, dependentes, escolaridade  
- **Financeiras**: salário anual, limite de crédito, tipo de cartão  
- **Comportamentais**: meses de relacionamento, número de produtos, transações e valor transacionado  
- **Variável alvo**: `default` (0 = adimplente, 1 = inadimplente)

---

## 🛠️ Ferramentas e Tecnologias

- **Python** (Pandas, NumPy)
- **SQL** para consultas analíticas
- **Jupyter Notebook / Google Colab / Kaggle**
- **AWS S3 + Athena** para leitura e análise dos dados via SQL
- **Visualização de dados** com gráficos estatísticos (barras, barras agrupado, pie chart)

---

## 🔍 Etapas da Análise

- Importação e inspeção inicial dos dados  
- Limpeza e padronização de colunas  
- Análise estatística descritiva  
- Análises segmentadas por:
  - Sexo
  - Escolaridade
  - Faixa salarial
  - Tipo de cartão
  - Default vs não default
- Consultas SQL para agregações e comparações  
- Visualização de padrões e tendências relevantes  

---

## 📈 Principais Insights (exemplos)

- Diferenças de comportamento financeiro entre clientes inadimplentes e adimplentes
- Relação entre **limite de crédito**, **volume de transações** e **default**
- Distribuição de clientes por faixa salarial e tipo de cartão
- Perfis de clientes com maior risco de inadimplência

---

## 📂 Estrutura do Projeto

├── credit-eda-and-analysis.ipynb # Notebook principal com EDA e SQL
├── credito.csv # Dataset de clientes de crédito
├── README.md # Documentação do projeto

---

## 🎯 Objetivo Final

Demonstrar habilidades em:

- Análise exploratória de dados
- Uso de **SQL aplicado a dados reais**
- Integração entre **Python e serviços em nuvem**
- Geração de insights a partir de dados financeiros
