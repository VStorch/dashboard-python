# 📊 Dashboard de Análise de Salários na Área de Dados

Aplicação web interativa desenvolvida em **Python** com **Streamlit** para análise de salários na área de dados ao longo dos anos.
O projeto foi criado durante a **Imersão de Dados em Python da Alura (2026)**, com foco em análise exploratória, visualização de dados e storytelling.

**Acesse o dashboard:**  
https://data-insights-python.streamlit.app/

---

## Funcionalidades

- Filtros interativos por:
  - Ano
  - Senioridade
  - Tipo de contrato
  - Tamanho da empresa
- Métricas gerais:
  - Salário médio anual (USD)
  - Salário máximo
  - Total de registros
  - Cargo mais frequente
- Visualizações interativas:
  - Top 10 cargos com maior salário médio
  - Distribuição de salários
  - Proporção dos tipos de trabalho (remoto / híbrido / presencial)
  - Mapa mundial com salário médio de **Data Scientists** por país
- Tabela com dados detalhados e filtros aplicados

---

## Contexto do Projeto

Este dashboard foi desenvolvido como parte da **Imersão de Dados em Python da Alura (2026)**, um evento intensivo focado em:

- Manipulação e análise de dados com **Pandas**
- Criação de visualizações interativas com **Plotly**
- Desenvolvimento de um dashboard interativo com **Streamlit**

O projeto consolida os conceitos aprendidos ao longo da imersão em uma aplicação prática e interativa.

---

## Tecnologias Utilizadas

- **Python**
- **Streamlit**
- **Pandas**
- **Plotly Express**

---

## Estrutura dos Dados

O dashboard utiliza um arquivo CSV contendo informações como:

- `ano`
- `senioridade`
- `contrato`
- `tamanho_empresa`
- `cargo`
- `usd` — salário anual em dólares
- `remoto`
- `residencia_iso3`

---

## Como Executar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/VStorch/dashboard-python.git
   ```

2. Instale as dependências:
    ```bash
   pip install -r requirements.txt
   ```

3. Execute a aplicação:
    ```
    streamlit run app.py
    ```
---

## Objetivo

Explorar dados salariais da área de dados, identificar padrões e praticar:

- Análise exploratória
- Visualização de dados
- Desenvolvimento de dashboards interativos em Python

---

## Autor
Vinícius Storch