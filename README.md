# Olá, eu sou o Leonardo 👋

**Desenvolvedor .NET** · C# · Blazor · ASP.NET Core · SQL Server · Campinas, SP

Há mais de dois anos trabalho com .NET: modernizo sistemas legados, otimizo bancos de dados e automatizo processos que antes eram manuais. Hoje desenvolvo e mantenho um ERP. Fora do trabalho, estudo arquitetura de software construindo projetos completos, do banco de dados à interface.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-leonardo--lira--siqueira-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leonardo-lira-siqueira)
[![E-mail](https://img.shields.io/badge/E--mail-leonardo018.siqueira@hotmail.com-EA4335?style=flat-square&logo=microsoftoutlook&logoColor=white)](mailto:leonardo018.siqueira@hotmail.com)

---

## ⭐ Projeto em destaque: [SmartStorage.Web](https://github.com/LeoLiras/SmartStorage.Web)

**Sistema de gestão de estoque e vendas em arquitetura de microsserviços .NET, com análise de dados por IA, inteiramente containerizado.**

![.NET](https://img.shields.io/badge/.NET_10-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Blazor](https://img.shields.io/badge/Blazor_WebAssembly-512BD4?style=flat-square&logo=blazor&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Docker](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Gemini](https://img.shields.io/badge/Google_Gemini-4285F4?style=flat-square&logo=google&logoColor=white)

O que o projeto exercita:

- **Microsserviços de verdade:** API principal, autenticação, relatórios, IA e e-mail, cada um com sua própria imagem Docker, atrás de um **API Gateway (Ocelot)**. Um único `docker compose up` sobe o sistema inteiro.
- **Segurança:** autenticação **JWT com refresh token**, papéis de acesso e sessão expirada levando de volta ao login.
- **Mensageria:** alertas de estoque mínimo publicados no **RabbitMQ** e enviados por e-mail por um serviço consumidor.
- **Regras de negócio consistentes:** histórico auditável de toda movimentação de estoque (quem, quando, quanto), devolução e transferência entre prateleiras, capacidade de prateleira por volume e operações em lote com **transação tudo ou nada**.
- **Dados e relatórios:** **Entity Framework Core** com migrations, listagens paginadas no servidor, relatórios em **PDF (QuestPDF)** e **Excel (ClosedXML)** e análises geradas pelo **Gemini**.
- **Front-end moderno:** **Blazor WebAssembly + MudBlazor**, com serviços tipados para cada domínio da API.
- **Qualidade:** **testes de componente com bUnit** rodando no CI, roteiro de testes ponta a ponta que confere os saldos no banco depois de cada operação, e **GitHub Actions** fazendo build, testes e publicação das imagens.

---

## 🛠️ Tecnologias

- **Back-end:** C# · .NET / ASP.NET Core · APIs REST · Entity Framework Core · Python · VB6 (migração de legado)
- **Front-end:** Blazor · MudBlazor · Windows Forms · DevExpress · HTML, CSS e JavaScript
- **Dados:** SQL Server (views, procedures e triggers) · PostgreSQL · Power BI
- **Infra e ferramentas:** Docker · RabbitMQ · GitHub Actions · Git · AWS · Robot Framework
- **Práticas:** SOLID · Clean Code · refatoração · testes automatizados · Scrum

---

## 💼 Experiência em resumo

- **Desenvolvedor .NET** (desde 2024): migração de módulos de um ERP de VB6 para .NET/C# e DevExpress, refatoração de rotinas, views e procedures no SQL Server e aplicações web em C# para automação e emissão de relatórios.
- **Estágio em P&D de software** (2023–2024): migração de software legado para .NET/C# em ambiente IoT, automação da atualização de firmware integrando Python a servidores AWS, testes de firmware com Robot Framework e implantação de Scrum na equipe.
- **Antes da programação:** projetos e manutenção industrial, com dashboards em Power BI, automação de relatórios e análise de indicadores.

## 🎓 Formação

- **Tecnólogo em Análise e Desenvolvimento de Sistemas** (2023–2024)
- **Técnico em Eletroeletrônica** (2018–2023)

---

<sub>Aberto a oportunidades como desenvolvedor .NET: presencial, híbrido ou remoto.</sub>
