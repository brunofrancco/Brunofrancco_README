<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=190&color=0:0E1420,100:2FA7A0&section=header&text=Bruno%20Franco&fontColor=FFFFFF&fontSize=58&fontAlignY=36&desc=An%C3%A1lise%20%26%20Engenharia%20de%20Dados&descSize=20&descAlignY=58&descColor=E8A33D" alt="Bruno Franco · Análise & Engenharia de Dados"/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=20&pause=1400&color=2FA7A0&center=true&vCenter=true&width=640&lines=Do+dado+bruto+ao+dado+confi%C3%A1vel;Do+dado+confi%C3%A1vel+%C3%A0+decis%C3%A3o;SQL+%C2%B7+ETL%2FELT+%C2%B7+Star+schema+%C2%B7+BI;Qualidade+de+dados+como+parte+do+pipeline)](https://brunofrancco.github.io/portifolio-de-projetos/)

<a href="https://brunofrancco.github.io/portifolio-de-projetos/"><img src="https://img.shields.io/badge/Portf%C3%B3lio-0E1420?style=for-the-badge&logo=githubpages&logoColor=E8A33D" alt="Portfólio"/></a>
<a href="https://www.linkedin.com/in/brunofrancco/"><img src="https://img.shields.io/badge/LinkedIn-0E1420?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyBmaWxsPSIjMkZBN0EwIiB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMjggMTI4Ij48cGF0aCBkPSJNMTE2IDNIMTJhOC45MSA4LjkxIDAgMDAtOSA4Ljh2MTA0LjQyYTguOTEgOC45MSAwIDAwOSA4Ljc4aDEwNGE4LjkzIDguOTMgMCAwMDktOC44MVYxMS43N0E4LjkzIDguOTMgMCAwMDExNiAzek0zOS4xNyAxMDdIMjEuMDZWNDguNzNoMTguMTF6bS05LTY2LjIxYTEwLjUgMTAuNSAwIDExMTAuNDktMTAuNSAxMC41IDEwLjUgMCAwMS0xMC41NCAxMC40OHpNMTA3IDEwN0g4OC44OVY3OC42NWMwLTYuNzUtLjEyLTE1LjQ0LTkuNDEtMTUuNDRzLTEwLjg3IDcuMzYtMTAuODcgMTVWMTA3SDUwLjUzVjQ4LjczaDE3LjM2djhoLjI0YzIuNDItNC41OCA4LjMyLTkuNDEgMTcuMTMtOS40MUMxMDMuNiA0Ny4yOCAxMDcgNTkuMzUgMTA3IDc1eiIvPjwvc3ZnPg==" alt="LinkedIn"/></a>
<a href="mailto:brunofranccofr@gmail.com"><img src="https://img.shields.io/badge/E--mail-0E1420?style=for-the-badge&logo=gmail&logoColor=E8A33D" alt="E-mail"/></a>

</div>

---

### `$ whoami`

Trabalho na interseção entre **Análise de Dados** e **Engenharia de Dados**: construo pipelines que entregam dados
confiáveis e transformo esses dados em indicadores, relatórios e dashboards que respondem às perguntas do negócio.

```yaml
bruno_franco:
  atuacao: [Análise de Dados, Engenharia de Dados]
  foco:    [SQL, ETL/ELT, modelagem dimensional, qualidade de dados, BI]
  status:  aberto a oportunidades como Analista de Dados ou Engenheiro de Dados
```

### `$ cat como-eu-trabalho.md`

```mermaid
flowchart LR
    A[Fontes<br/>APIs · bancos · arquivos] --> B[Ingestão<br/>Python · ETL/ELT]
    B --> C{Qualidade<br/>de dados}
    C -- ok --> D[(Modelagem<br/>star schema)]
    C -- falha --> Q[Quarentena]
    D --> E[Indicadores<br/>SQL]
    E --> F[Dashboards e<br/>relatórios]
    F --> G((Decisão))
```

Cada projeto meu segue esse fluxo: **nenhum número chega ao negócio sem passar por validação**.

---

### `$ ls projetos/`

| | Projeto | O que entrega | Stack |
|:-:|---|---|---|
| 🛠️ | [**Plataforma de dados de RH**](https://github.com/brunofrancco/people-analytics-data-platform) | Pipeline ELT no Google Cloud: API de RH → BigQuery → star schema com dbt, orquestrado com Airflow e com dados pessoais mascarados (LGPD) | `BigQuery` `dbt` `Airflow` `Terraform` |
| 🛠️ | [**Analytics Engineering de e-commerce**](https://github.com/brunofrancco/ecommerce-analytics-engineering) | Da API REST ao dashboard: star schema em DuckDB, validações automáticas de qualidade e KPIs de receita e clientes | `Python` `DuckDB` `SQL` `Streamlit` |
| 🛠️ | [**Pipeline de uma seguradora digital**](https://github.com/brunofrancco/insurance-data-analytics) | 15 regras de qualidade com quarentena, star schema com snapshot mensal, 8 indicadores em SQL e relatórios automatizados | `Python` `SQL` `Pandas` `GitHub Actions` |
| 📊 | [**Superstore Sales Analytics**](https://github.com/brunofrancco/Analise-Exploratoria-de-Dados-Superstore-Sales-Analytics) | Mostrou que 100% dos pedidos com desconto de 50% ou mais dão prejuízo; Pareto, RFM e dashboard interativo | `Pandas` `SciPy` `Plotly` `Streamlit` |
| 📊 | [**Customer Analytics: qualidade de dados**](https://github.com/brunofrancco/customer-analytics-data-quality-eda) | Encontrou e removeu 180 clientes duplicados de uma base vinda de vários sistemas, com deduplicação por similaridade de nomes | `Pandas` `RapidFuzz` `SciPy` `pytest` |

<sub>🛠️ engenharia de dados · 📊 análise de dados — detalhes de cada um no [portfólio](https://brunofrancco.github.io/portifolio-de-projetos/).</sub>

---

### `$ stack --list`

| Área | Ferramentas |
|---|---|
| **Linguagens e análise** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/python/python-original.svg" width="34" title="Python"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/pandas/pandas-original.svg" width="34" title="Pandas"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/numpy/numpy-original.svg" width="34" title="NumPy"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/jupyter/jupyter-original.svg" width="34" title="Jupyter"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/plotly/plotly-original.svg" width="34" title="Plotly"/> · SQL, estatística e testes de hipótese |
| **Bancos de dados** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/postgresql/postgresql-original.svg" width="34" title="PostgreSQL"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/mysql/mysql-original.svg" width="34" title="MySQL"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/sqlite/sqlite-original.svg" width="34" title="SQLite"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/duckdb/duckdb-original.svg" width="34" title="DuckDB"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/oracle/oracle-original.svg" width="34" title="Oracle"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/mongodb/mongodb-original.svg" width="34" title="MongoDB"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/cassandra/cassandra-original.svg" width="34" title="Cassandra"/> · BigQuery |
| **Engenharia e orquestração** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/apacheairflow/apacheairflow-original.svg" width="34" title="Apache Airflow"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/fastapi/fastapi-original.svg" width="34" title="FastAPI"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/docker/docker-original.svg" width="34" title="Docker"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/terraform/terraform-original.svg" width="34" title="Terraform"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/git/git-original.svg" width="34" title="Git"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/githubactions/githubactions-original.svg" width="34" title="GitHub Actions"/> · dbt |
| **Cloud** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/googlecloud/googlecloud-original.svg" width="34" title="Google Cloud"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="34" title="AWS"/> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/azure/azure-original.svg" width="34" title="Azure"/> |
| **BI e visualização** | <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.17.0/icons/streamlit/streamlit-original.svg" width="34" title="Streamlit"/> · Power BI · Tableau · Looker Studio · Metabase |

---

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=brunofrancco&show_icons=true&hide_border=true&bg_color=0E1420&title_color=E8A33D&icon_color=2FA7A0&text_color=B9C2D0&custom_title=Atividade%20no%20GitHub" alt="Estatísticas do GitHub"/>
<img height="165" src="https://streak-stats.demolab.com?user=brunofrancco&hide_border=true&background=0E1420&ring=2FA7A0&fire=E8A33D&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=E8A33D&sideLabels=B9C2D0&dates=B9C2D0&locale=pt_BR" alt="Sequência de contribuições"/>

</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Brunofrancco/Brunofrancco/output/github-contribution-grid-snake-dark.svg">
  <img width="100%" src="https://raw.githubusercontent.com/Brunofrancco/Brunofrancco/output/github-contribution-grid-snake.svg" alt="Animação da cobrinha comendo as contribuições">
</picture>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:2FA7A0,100:0E1420&section=footer" alt=""/>
