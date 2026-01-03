# 📊 Análise de Dados de Vendas / Sales Data Analysis

---

## 🇧🇷 Visão Geral do Projeto

Este projeto apresenta uma **análise exploratória de dados (EDA)** aplicada a um conjunto de dados de vendas de uma loja, com foco em **tratamento, transformação, análise e visualização de dados** para geração de  **insights estratégicos de negócio** .

A análise foi desenvolvida utilizando  **Python, Pandas e Matplotlib** , reproduzindo um fluxo de trabalho comum em ambientes corporativos orientados por dados.

---

## 🇺🇸 Project Overview

This project presents an **exploratory data analysis (EDA)** applied to a retail sales dataset, focusing on **data cleaning, transformation, analysis, and visualization** to generate  **actionable business insights** .

The analysis was developed using  **Python, Pandas, and Matplotlib** , following a workflow commonly adopted in  **data-driven business environments** .

---

## 🇧🇷 Objetivos do Projeto

* Garantir **qualidade e consistência dos dados**
* Realizar **limpeza e tratamento** de dados incompletos ou inconsistentes
* Extrair **indicadores-chave de desempenho (KPIs)**
* Identificar **produtos mais vendidos e mais lucrativos**
* Analisar **receita por pedido e por período**
* Apoiar a **tomada de decisão baseada em dados**

---

## 🇺🇸 Project Objectives

* Ensure **data quality and consistency**
* Perform **data cleaning and preprocessing**
* Extract **key performance indicators (KPIs)**
* Identify **top-selling and most profitable products**
* Analyze **revenue per order and over time**
* Support **data-driven decision making**

---

## 🛠️ Tecnologias e Ferramentas | Technologies & Tools

* **Python 3**
* **Pandas** – data manipulation and aggregation
* **Matplotlib** – data visualization
* **Jupyter Notebook / VS Code**
* **CSV file** as data source

---

## 📁 Estrutura do Projeto | Project Structure

```
data-analysis-vendas
├── data
│   ├── raw
│   │   └── loja_pedidos.csv
│   └── processed
│       └── loja_pedidos_tratado.csv
│
├── notebooks
│   └── analysis.ipynb
│
├── outputs
│   ├── figures
│   │   ├── revenue_by_month_1sem_2024.png
│   │   ├── best_sellers_bar.png
│   │   └── best_sellers_pie.png
│   └── reports
│       └── top_10_sellers.xlsx
│
├── README.md
└── requirements.txt

```

---

## 🇧🇷 Tratamento e Preparação dos Dados

As seguintes etapas foram executadas para assegurar a confiabilidade da análise:

* Identificação de **valores nulos e campos vazios**
* Padronização de descrições ausentes
* Limpeza e conversão da coluna `item_price`
* Preenchimento de valores ausentes com:
  * **Moda por produto**
  * **Média** , quando necessário
* Conversão da coluna `order_date` para o tipo `datetime`

---

## 🇺🇸 Data Preparation & Cleaning

The following steps were performed to ensure analytical reliability:

* Detection of **null and empty values**
* Standardization of missing product descriptions
* Cleaning and conversion of the `item_price` column
* Imputation of missing values using:
  * **Mode per product**
  * **Mean** , when applicable
* Conversion of the `order_date` column to `datetime`

---

## 🇧🇷 Análises e Métricas Calculadas

* Total de **pedidos únicos**
* Total de **itens distintos vendidos**
* **Item mais vendido** por quantidade
* **Item com maior receita**
* **Receita média por pedido**
* **Pedido com maior valor total**
* **Dia com maior faturamento**
* Combinação **item × descrição** mais vendida

---

## 🇺🇸 Key Metrics & Analysis

* Total number of **unique orders**
* Total number of **distinct items sold**
* **Best-selling product** by quantity
* **Highest-revenue product**
* **Average revenue per order**
* **Highest-value order**
* **Top revenue day**
* Most sold **item–description combination**

---

## 📊 Visualizações | Data Visualizations

* **Top 10 produtos mais vendidos** – Bar Chart
* **Top 10 produtos mais vendidos** – Pie Chart
* **Top 10 produtos com maior receita** – Line Chart

All visual outputs are automatically exported to the `results` directory.

---

## 💡 Principais Insights | Key Insights

* Identificação de produtos com **alto volume de vendas**
* Diferença clara entre **volume de vendas e geração de receita**
* Concentração de faturamento em poucos produtos
* Identificação de **picos de faturamento ao longo do tempo**

---

## 📤 Exportação de Dados | Data Export

### 🇧🇷 Exportação dos 10 Itens Mais Vendidos

Além das análises e visualizações, o projeto também realiza a **exportação dos 10 produtos mais vendidos** para um **arquivo Excel (.xlsx)**.

O arquivo exportado contém:

- Identificação do produto
- Quantidade total vendida
- Dados consolidados para uso em relatórios e análises externas

Essa funcionalidade facilita o compartilhamento dos resultados com equipes de negócio e possibilita o uso dos dados em ferramentas como **Excel, Power BI e Google Sheets**.

O arquivo é gerado automaticamente durante a execução da análise e salvo no diretório do projeto.

---

### 🇺🇸 Top 10 Best-Selling Items Export

In addition to the analyses and visualizations, the project also **exports the top 10 best-selling products** to an **Excel file (.xlsx)**.

The exported file includes:

- Product identification
- Total quantity sold
- Consolidated data ready for reporting and external analysis

This feature allows easy data sharing with business teams and supports further analysis using tools such as **Excel, Power BI, and Google Sheets**.

The file is automatically generated during the analysis execution and saved in the project directory.

## 🎯 Relevância Profissional | Professional Relevance

Este projeto demonstra competências essenciais em  **Análise de Dados** , incluindo:

* Data cleaning and preprocessing
* KPI definition and calculation
* Business-oriented data analysis
* Clear and effective data visualization
* Well-structured and documented analytical projects

---

## Autora | Author

**Fernanda Morello**
Análise de Dados | Data Science
