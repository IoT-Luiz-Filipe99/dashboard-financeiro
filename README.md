# 💰 Dashboard Financeiro & Analítico

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Dash](https://img.shields.io/badge/Frontend-Dash%20%7C%20Streamlit-00796B)
![Pandas](https://img.shields.io/badge/Data-Pandas-150458)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)

## 📋 Sobre o Projeto

Este projeto é um **Painel de Controle Financeiro** desenvolvido para transformar planilhas de dados brutos (`.xlsx` / `.csv`) em insights visuais acionáveis. O sistema processa grandes volumes de dados financeiros para apresentar indicadores de desempenho (KPIs) claros.

O objetivo é eliminar a dependência de relatórios estáticos em Excel, oferecendo uma visão interativa de receitas, despesas e margem de lucro.

## ✨ Principais Funcionalidades

* **Visão Geral Financeira:** Cards com totalizadores de Receita, Custo e Lucro Líquido.
* **Análise Temporal:** Gráficos de linha para acompanhamento de tendências (Mês a Mês / Ano a Ano).
* **Categorização:** Breakdown de despesas por centro de custo ou categoria.
* **Processamento de Dados:** Script ETL (`dbf.py`) capaz de tratar e unificar bases de dados.
* **Exportação:** Capacidade de gerar relatórios tratados baseados na planilha `df_final_dashboard.xlsx`.

## 🚀 Tecnologias Utilizadas

* **Linguagem:** Python
* **Manipulação de Dados:** Pandas
* **Visualização:** Plotly / Dash
* **Base de Dados:** Excel (Fonte de Dados)

## 📦 Como Rodar Localmente

### Pré-requisitos
* Python 3.8+
* Git

### Passo a Passo

1.  **Clone o repositório**
    ```bash
    git clone [https://github.com/IoT-Luiz-Filipe99/dashboard-main.git](https://github.com/IoT-Luiz-Filipe99/dashboard-main.git)
    cd dashboard-main
    ```

2.  **Instale as dependências**
    ```bash
    pip install pandas plotly dash openpyxl
    ```

3.  **Execute a Aplicação**
    *Se for um app Dash:*
    ```bash
    python index.py
    ```
    *Se for Streamlit:*
    ```bash
    streamlit run app.py
    ```

4.  **Acesse**
    O painel estará disponível no seu navegador (geralmente em `http://127.0.0.1:8050` ou `localhost:8501`).

## 📄 Licença

Este projeto está sob a licença MIT.