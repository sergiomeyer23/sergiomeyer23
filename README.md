<a name="english"></a>
<p align="center">
  <img src="banner.jpg" alt="Sérgio Meyer — Data Analyst & Developer" width="100%" />
</p>
<div align="center">

<img src="https://avatars.githubusercontent.com/u/90986811?v=4" width="112" height="112" alt="Sérgio Meyer" />

# Sérgio Meyer

### Data Analyst & Developer

*I turn operational data into business decisions — and build the tools that automate them.*

📍 Cascavel, Paraná, Brazil &nbsp;·&nbsp; 🎯 Open to Data Analyst roles

<br />

[![Portfolio](https://img.shields.io/badge/PORTFOLIO-sergiomeyer23.github.io-0969da?style=for-the-badge&logo=githubpages&logoColor=white)](LINK_PORTFOLIO)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-in%2Fsergio--meyer-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](LINK_LINKEDIN)
[![Email](https://img.shields.io/badge/EMAIL-SEU_EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:SEU_EMAIL)

<br />

[`🇧🇷 Ler em Português`](#portugues)

</div>

---

## About

I work at the intersection of **business and data**. My background is in commercial routines — sales performance, customer portfolios, retail operations — so when I open a dashboard I'm looking for the *decision* behind the chart, not just the chart.

Today I build analysis pipelines in **Python** (Pandas, Plotly, Streamlit) over **PostgreSQL**, and I also ship applications in **Java/Spring Boot** and **TypeScript/Next.js** when a spreadsheet stops being enough.

```
🔭 Currently building ···· Falow AI — a personal AI English teacher (Next.js + Spring Boot)
📊 Currently analysing ··· Marketplace logistics vs. customer satisfaction
🌱 Currently learning ···· Advanced SQL (window functions), DAX & Power BI
💬 Ask me about ··········· Sales analysis, ETL in Python, dashboard design
```

---

## Stack

<div align="center">

**Data & Analytics**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Development**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</div>

---

## Featured Projects

### 📊 [Olist — Sales Performance Analysis](https://github.com/sergiomeyer23/olist-sales-performance-analysis)

Exploratory analysis and an interactive **Streamlit dashboard** over **96,000 delivered orders** (R$ 13.2M GMV) from Brazil's largest marketplace.

| Key findings | Number |
|:---|---:|
| **Late delivery destroys the rating** — the most actionable insight in the dataset | 4.29 on time → **2.57** late |
| Real Pareto among sellers: 18% of sellers generate 80% of revenue | **18% → 80%** |
| Extreme geographic concentration in the Southeast | SP + RJ + MG = **63%** |
| Freight as a share of price penalises North/Northeast | **22.7%** vs 13.1% |

> **Business read:** *logistics is the product.* Only 8.1% of orders are late, but 46% of those get a 1-star review — the problem is concentrated, therefore treatable.

`Python` `Pandas` `Plotly` `Streamlit` `PostgreSQL` `ETL`

---

### 🎓 [Falow AI — Personal English Teacher](https://github.com/sergiomeyer23/FalowAI) &nbsp;·&nbsp; [🔗 Live demo](https://falow-ai.vercel.app)

Full-stack product: a personal English learning environment with CEFR profiling, a gamified XP engine, and a speaking lab using native browser speech recognition.

- XP calculated by a single `XPService` with **anti-farming decay** for repetitions
- CEFR level derived from assessment evidence per skill — *not* from XP
- Transparent rule-based recommendation engine; AI is not used to fake answers the system cannot produce
- Backend prepared for PostgreSQL + Flyway + JWT, with versioned prompts outside the code

`TypeScript` `Next.js` `Tailwind` `Spring Boot` `PostgreSQL` `Flyway` `JWT` `Docker`

---

### 🧾 [Sales Report Automation](https://github.com/sergiomeyer23/automaticao-planilha)

Java CLI application that reads a raw `.xlsx` sales spreadsheet and generates a consolidated monthly management report — 3 tabs (monthly summary, sales by product, top 5) with KPIs printed to the terminal. Handles messy real-world input: dates as `DD/MM/YYYY` *or* `YYYY-MM-DD`, prices as `3.49` *or* `R$ 1.234,56`.

`Java 11+` `Apache POI 5.3` `Maven`

---

### 💰 [Personal Finance API](https://github.com/sergiomeyer23/personal-finance-api)

REST API for personal finance management — users, accounts, categories and transactions modelled with JPA.

`Java` `Spring Boot` `Spring Data JPA` `Maven` `H2/PostgreSQL`

---

### 🔬 [More data projects](https://github.com/sergiomeyer23?tab=repositories&q=&type=&language=python&sort=stargazers)

**[Retail Sales Analyzer](https://github.com/sergiomeyer23/retail-sales-analyzer)** — CSV sales analysis: totals, average ticket, most/least expensive product, revenue leader and configurable value filters, with per-file / per-column / per-value error handling.

**[Pandas Fundamentals](https://github.com/sergiomeyer23/pandas-fundamentos)** — a 12-lab track covering reading, cleaning, filtering, `groupby` and `merge`.

**[Excel Dashboard — Sales & Inventory](https://github.com/sergiomeyer23/excel-dashboard-vendas-estoque-)** — out-of-stock products, stores below target and most profitable categories.

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sergiomeyer23&layout=compact&hide_border=true&bg_color=00000000&title_color=1f6feb&text_color=8b949e&langs_count=8&exclude=olist-sales-performance-analysis,Stopwatch-Project" alt="Most used languages" width="46%" />

<!--
  Card de estatísticas (estrelas, commits, PRs) — DEIXEI DESATIVADO DE PROPÓSITO.
  Com 0 estrelas e ~43 commits públicos, ele mais prejudica do que ajuda hoje.
  Reative quando tiver tração, apagando as linhas de comentário abaixo:

<img src="https://github-readme-stats.vercel.app/api?username=sergiomeyer23&show_icons=true&hide_border=true&bg_color=00000000&title_color=1f6feb&icon_color=1f6feb&text_color=8b949e&count_private=true" alt="GitHub stats" width="46%" />
-->

</div>

---

## Contact

Reach out — I answer everything.

📧 **sergio.gabriel.meyer10@gmail.com** &nbsp;·&nbsp; 💼 **[Sérgio Meyer](https://www.linkedin.com/in/s%C3%A9rgio-meyer-7aaa45407/)** &nbsp;·&nbsp; 🌐 **[Portfolio](github.com/sergiomeyer23)**

<div align="center">

[![EN](https://img.shields.io/badge/⬆_Back_to_top-0969da?style=flat-square)](#english)

</div>

<br />
<br />

<a name="portugues"></a>

<!-- ══════════════════════════ PORTUGUÊS ══════════════════════════ -->

<div align="center">
<p align="center">
  <img src="banner.jpg" alt="Sérgio Meyer — Data Analyst & Developer" width="100%" />
</p>

<img src="https://avatars.githubusercontent.com/u/90986811?v=4" width="112" height="112" alt="Sérgio Meyer" />

# Sérgio Meyer

### Analista de Dados & Desenvolvedor

*Transformo dados operacionais em decisões de negócio — e construo as ferramentas que automatizam isso.*

📍 Cascavel, Paraná, Brasil &nbsp;·&nbsp; 🎯 Aberto a vagas de Analista de Dados

<br />

[![Portfólio](https://img.shields.io/badge/PORTFÓLIO-sergiomeyer23.github.io-0969da?style=for-the-badge&logo=githubpages&logoColor=white)](LINK_PORTFOLIO)
[![LinkedIn](https://img.shields.io/badge/LINKEDIN-in%2Fsergio--meyer-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](LINK_LINKEDIN)
[![E-mail](https://img.shields.io/badge/EMAIL-SEU_EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:SEU_EMAIL)

<br />

[`🇬🇧 Read in English`](#english)

</div>

---

## Sobre

Atuo na fronteira entre **negócio e dados**. Minha formação prática vem de rotinas comerciais — desempenho de vendas, carteira de clientes, operação de varejo — então, ao abrir um dashboard, procuro a *decisão* por trás do gráfico, não apenas o gráfico.

Hoje construo pipelines de análise em **Python** (Pandas, Plotly, Streamlit) sobre **PostgreSQL**, e também entrego aplicações em **Java/Spring Boot** e **TypeScript/Next.js** quando a planilha deixa de ser suficiente.

```
🔭 Construindo agora ···· Falow AI — professor de inglês pessoal com IA (Next.js + Spring Boot)
📊 Analisando agora ····· Logística de marketplace vs. satisfação do cliente
🌱 Aprendendo ··········· SQL avançado (window functions), DAX e Power BI
💬 Pode me perguntar ···· Análise de vendas, ETL em Python, design de dashboards
```

---

## Stack

<div align="center">

**Dados & Análise**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)

**Bancos de Dados**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Desenvolvimento**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Ferramentas**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

</div>

---

## Projetos em Destaque

### 📊 [Olist — Análise de Performance de Vendas](https://github.com/sergiomeyer23/olist-sales-performance-analysis)

Análise exploratória e **dashboard interativo em Streamlit** sobre **96 mil pedidos entregues** (R$ 13,2 milhões em GMV) do maior marketplace brasileiro.

| Principais descobertas | Número |
|:---|---:|
| **Atraso na entrega derruba a avaliação** — o achado mais acionável da base | 4,29 no prazo → **2,57** atrasado |
| Pareto real entre vendedores: 18% geram 80% da receita | **18% → 80%** |
| Concentração geográfica extrema no Sudeste | SP + RJ + MG = **63%** |
| Frete sobre o preço penaliza Norte/Nordeste | **22,7%** vs 13,1% |

> **Leitura de negócio:** *logística é o produto.* Apenas 8,1% dos pedidos atrasam, mas 46% deles recebem nota 1 — o problema é concentrado e, por isso, tratável.

`Python` `Pandas` `Plotly` `Streamlit` `PostgreSQL` `ETL`

---

### 🎓 [Falow AI — Professor de Inglês Pessoal](https://github.com/sergiomeyer23/FalowAI) &nbsp;·&nbsp; [🔗 Demo online](https://falow-ai.vercel.app)

Produto full-stack: ambiente pessoal de aprendizagem de inglês com perfil CEFR, engine de XP gamificado e laboratório de speaking usando reconhecimento de fala nativo do navegador.

- XP calculado em um único `XPService`, com **decaimento anti-farming** para repetições
- Nível CEFR derivado das evidências de avaliação por habilidade — *não* do XP
- Engine de recomendação baseada em regras transparentes; IA não é usada para inventar resposta que o sistema não consegue produzir
- Backend preparado para PostgreSQL + Flyway + JWT, com prompts versionados fora do código

`TypeScript` `Next.js` `Tailwind` `Spring Boot` `PostgreSQL` `Flyway` `JWT` `Docker`

---

### 🧾 [Automação de Relatório de Vendas](https://github.com/sergiomeyer23/automaticao-planilha)

Aplicação Java de linha de comando que lê uma planilha `.xlsx` de vendas brutas e gera um relatório gerencial consolidado do mês — 3 abas (resumo do mês, vendas por produto, top 5) com indicadores no terminal. Trata entrada suja do mundo real: datas em `DD/MM/AAAA` *ou* `AAAA-MM-DD`, preços como `3.49` *ou* `R$ 1.234,56`.

`Java 11+` `Apache POI 5.3` `Maven`

---

### 💰 [API de Finanças Pessoais](https://github.com/sergiomeyer23/personal-finance-api)

API REST para gestão de finanças pessoais — usuários, contas, categorias e transações modelados com JPA.

`Java` `Spring Boot` `Spring Data JPA` `Maven` `H2/PostgreSQL`

---

### 🔬 [Mais projetos de dados](https://github.com/sergiomeyer23?tab=repositories&q=&type=&language=python&sort=stargazers)

**[Analisador de Vendas no Varejo](https://github.com/sergiomeyer23/retail-sales-analyzer)** — análise de vendas em CSV: totais, ticket médio, produto mais caro/mais barato, líder de receita e filtros de valor configuráveis, com tratamento de erro por arquivo, por coluna e por valor.

**[Fundamentos de Pandas](https://github.com/sergiomeyer23/pandas-fundamentos)** — trilha de 12 laboratórios cobrindo leitura, limpeza, filtros, `groupby` e `merge`.

**[Dashboard Excel — Vendas e Estoque](https://github.com/sergiomeyer23/excel-dashboard-vendas-estoque-)** — produtos sem estoque, lojas abaixo da meta e categorias mais rentáveis.

<div align="center">

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sergiomeyer23&layout=compact&hide_border=true&bg_color=00000000&title_color=1f6feb&text_color=8b949e&langs_count=8&exclude=olist-sales-performance-analysis,Stopwatch-Project" alt="Linguagens mais usadas" width="46%" />

</div>

---

## Contato

Pode chamar — respondo tudo.

📧 **sergio.gabriel.meyer10@gmail.com** &nbsp;·&nbsp; 💼 **[Sérgio Meyer](https://www.linkedin.com/in/s%C3%A9rgio-meyer-7aaa45407/)** &nbsp;·&nbsp; 🌐 **[Portfólio](github.com/sergiomeyer23)**

<div align="center">

[![PT](https://img.shields.io/badge/⬆_Voltar_ao_topo-0969da?style=flat-square)](#portugues)

</div>
