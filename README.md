# Sérgio Meyer

**Data & Software Engineer | Python · SQL · TypeScript · Java (Spring Boot)**

📍 Cascavel, PR, Brasil

[](https://sergiomeyer23.github.io/portfolio/)
[LinkedIn](https://www.google.com/search?q=https://www.linkedin.com/in/sergio-meyer-7aaa45407)
[](mailto:sergio.gabriel.meyer10@gmail.com)

Construo pipelines de dados, automações operacionais e aplicações backend/web que transformam dados brutos em decisões de negócio. Atuo na interseção entre **Engenharia/Análise de Dados** e **Engenharia de Software**, desenvolvendo desde coletores distribuídos e modelos analíticos em Python/SQL até APIs REST em Java (Spring Boot) e interfaces reativas em TypeScript/React — sempre com testes automatizados e integração contínua (CI/CD).

## Contribuições Open Source em Destaque

* **[Bayer-Group/MotherML](https://github.com/Bayer-Group/MotherML)** ([Fork no Perfil](https://github.com/sergiomeyer23/MotherML)) — Framework de Machine Learning em Python mantido pelo grupo Bayer para predição de propriedades moleculares e dados de transcriptômica:
  * **PR #91 (Model Registry):** Implementação de registro unificado para descoberta e instanciação padronizada de modelos (CatBoost, Random Forest, Lasso, TabPFN e estimadores customizados compatíveis com Scikit-Learn).
  * **PR #106 (Murcko Scaffold Grouping):** Agrupamento baseado em estruturas químicas (*Murcko scaffolds*) para validação cruzada consciente de domínio, evitando *data leakage* entre compostos estruturalmente similares.

## Projetos em Produção e Estudos de Caso

| Projeto | Domínio | Arquitetura, Engenharia e Impacto | Stack Principal |
| :--- | :--- | :--- | :--- |
| **[Mercavel](https://github.com/sergiomeyer23/Mercavel)** ([App Online](https://sergiomeyer23.github.io/Mercavel/)) | Engenharia de Dados & Full-Stack | Comparador e rastreador diário de preços entre supermercados de Cascavel/PR. Coleta automatizada e paralelizada em 4 *shards* via GitHub Actions, pipeline de *entity resolution* em duas etapas (pareamento exato por EAN + heurística normalizada de marca/nome/gramatura) e testes automatizados. | TypeScript, React, Node.js, Supabase, Vitest, GitHub Actions |
| **[weg_equity_pipeline](https://github.com/sergiomeyer23/weg_equity_pipeline)** | Engenharia de Dados & Finanças Quantitativas | Pipeline ETL modular que extrai demonstrativos regulatórios da CVM e cotações do Yahoo Finance para a WEG (`WEGE3.SA`), calcula múltiplos fundamentalistas, executa valuation por Fluxo de Caixa Descontado (DCF) e publica dashboard interativo com suporte a execução determinística (`--mock` e `--live`). | Python, Pandas, Streamlit, Pytest, GitHub Actions |
| **[print-guard](https://github.com/sergiomeyer23/print-guard)** | Automação de Sistemas & Backend Python | Utilitário CLI para agendamento, auditoria de fila de impressão (spooler) e emissão de alertas em ambientes corporativos Windows. Utiliza banco SQLite local com controle de *lock/journal* para garantir idempotência e evitar impressões duplicadas, com releases versionadas (`v0.2.1` / `v0.3.0rc1`). | Python, SQLite, ReportLab, Windows Task Scheduler, Pytest |
| **[expense-tracker-api](https://github.com/sergiomeyer23/expense-tracker-api)** | Engenharia Backend (REST API) | API REST para gestão financeira pessoal construída em arquitetura em camadas (`Controller`, `Service`, `Repository`), com validação estrita via DTOs, tratamento global de exceções, persistência relacional e ambiente conteinerizado. | Java 21, Spring Boot, Spring Data JPA, PostgreSQL, Docker Compose, JUnit 5 |
| **[olist-sales-performance-analysis](https://github.com/sergiomeyer23/olist-sales-performance-analysis)** | Analytics Engineering & Business Intelligence | Análise de performance logística, SLA de entregas, satisfação de clientes (NPS/reviews) e concentração de Pareto sobre 96 mil pedidos reais do marketplace Olist, separando o motor de cálculo em Python da camada de visualização. | Python, Pandas, Plotly, Streamlit, Pytest, GitHub Actions |
| **[automacao-planilha](https://github.com/sergiomeyer23/automacao-planilha)** | Automação Corporativa & ETL em Java | Ferramenta CLI que higieniza bases de vendas despadronizadas em Excel (`.xlsx`) e gera relatórios gerenciais consolidados com indicadores por categoria e produto, validada por suíte de testes no CI. | Java, Apache POI, JUnit, GitHub Actions |
| **[FalowAI](https://github.com/sergiomeyer23/FalowAI)** | Produto Full-Stack & EdTech | Plataforma de aprendizado adaptativo de inglês com laboratório de pronúncia, dashboard de progresso e motor de gamificação com regras anti-farming de XP testadas no backend. | TypeScript, Next.js, Java, Spring Boot |

## Stack Técnica e Práticas de Engenharia

| Área | Tecnologias e Ferramentas |
| :--- | :--- |
| **Engenharia & Análise de Dados** | Python, Pandas, SQL (PostgreSQL, SQLite), ETL/ELT Pipelines, Data Cleaning & Entity Resolution, Power BI, Streamlit, Plotly |
| **Desenvolvimento Backend & Web** | Java 21, Spring Boot, Spring Data JPA, REST APIs, TypeScript, React, Next.js, Node.js, HTML5, CSS3 / Tailwind CSS |
| **Qualidade, Testes & DevOps** | GitHub Actions (CI/CD & Cron Workflows), Docker, Docker Compose, Pytest, JUnit 5, Mockito, Vitest, ESLint, Prettier, Git |

## Contato

* **Portfólio Completo e Estudos de Caso:** [sergiomeyer23.github.io/portfolio](https://sergiomeyer23.github.io/portfolio/)
* **LinkedIn:** [linkedin.com/in/sergio-meyer-7aaa45407](https://www.google.com/search?q=https://www.linkedin.com/in/sergio-meyer-7aaa45407)
* **E-mail:** [sergio.gabriel.meyer10@gmail.com](mailto:sergio.gabriel.meyer10@gmail.com)