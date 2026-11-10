# 📊 Dashboard de Análise de Salários na Área de Dados

Dashboard interativo desenvolvido em Python para explorar e analisar salários de profissionais da área de dados ao longo dos anos. A aplicação permite filtrar informações por diferentes critérios e visualizar indicadores e gráficos que facilitam a compreensão do mercado de trabalho.

## 🚀 Funcionalidades

- **Filtros interativos:** seleção por ano, senioridade, tipo de contrato e tamanho da empresa.
- **Indicadores gerais (KPIs):** salário médio, salário máximo, total de registros e cargo mais frequente.
- **Análise de cargos:** visualização dos 10 cargos com maiores médias salariais.
- **Distribuição salarial:** análise da distribuição dos salários anuais.
- **Modalidade de trabalho:** comparação da proporção entre os tipos de trabalho.
- **Análise geográfica:** visualização do salário médio de Cientistas de Dados por país.
- **Dados detalhados:** tabela interativa com os registros após aplicação dos filtros.

## 🛠️ Tecnologias utilizadas

- **Python:** linguagem utilizada no desenvolvimento da aplicação.
- **Streamlit:** criação da interface interativa e dos filtros.
- **Pandas:** carregamento, manipulação e análise dos dados.
- **Plotly Express:** construção de gráficos interativos.

## 📂 Fonte dos dados

Os dados são obtidos diretamente de um arquivo CSV disponibilizado no GitHub:

[Dataset de Salários na Área de Dados](https://github.com/vqrca/dashboard_salarios_dados)

A aplicação carrega os dados diretamente da fonte, sem necessidade de armazenar o arquivo CSV localmente.

## ⚙️ Como executar o projeto

**1. Clone o repositório:**

```bash
git clone <URL_DO_REPOSITORIO>
cd <NOME_DO_REPOSITORIO>
```

**2. Crie e ative um ambiente virtual (opcional):**

```bash
python -m venv venv
```

Windows:

```bash
venv\Scripts\activate
```

Linux/macOS:

```bash
source venv/bin/activate
```

**3. Instale as dependências:**

```bash
pip install streamlit pandas plotly
```

**4. Execute a aplicação:**

```bash
streamlit run app.py
```

A aplicação será disponibilizada localmente pelo Streamlit, permitindo explorar os dados por meio dos filtros e gráficos interativos.

## 📈 Análises disponíveis

O dashboard apresenta diferentes perspectivas sobre o mercado de trabalho na área de dados, permitindo explorar informações salariais por cargo, senioridade, modalidade de trabalho, tipo de contrato, porte da empresa e localização geográfica.
