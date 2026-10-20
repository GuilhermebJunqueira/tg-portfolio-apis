# Portfólio de Aprendizagem de Projetos Integrados (API)

Trabalho de Graduação (TG), modelo Portfólio, do curso de Banco de Dados da Fatec São José dos Campos – Prof. Jessen Vidal.

Este repositório reúne o resumo dos quatro projetos integradores (API) desenvolvidos do 1º ao 4º semestre. A **API de destaque** é a do 4º semestre.

**Autor:** Guilherme Bezerra Junqueira  
**Orientador:** Prof. Carlos Augusto Lombardi Garcia  
**Documento completo:** [TG_Portfolio_Guilherme_Junqueira.pdf](TG_Portfolio_Guilherme_Junqueira.pdf)

## Visão geral

| Semestre | Projeto | Período | Tema |
|---|---|---|---|
| 1º | [API-Porygon](https://github.com/Porygon-Users/API-Porygon) | 04/09/2023 a 26/11/2023 | Gestão de turmas, grupos e scores (PBL) |
| 2º | [Leitor-de-clima](https://github.com/VCCorpTeam/Leitor-de-clima) | 25/03/2024 a 16/06/2024 | Leitura e análise de dados climáticos em CSV |
| 3º | [FATEC-API-3-SEMESTRE](https://github.com/c137santos/FATEC-API-3-SEMESTRE) | 09/09/2024 a 01/12/2024 | Captura de notícias e APIs públicas (web scraping) |
| 4º | [CaramelStray-Api-4Semestre](https://github.com/CaramelStray/CaramelStray-Api-4Semestre) | 16/03/2026 a 31/05/2026 | Sistema de Gestão de Manutenções (**API de destaque**) |

---

## 1º semestre: API-Porygon (2023-2)

**Desafio.** A PBLTeX, instituição que ensina com PBL (aprendizagem baseada em problemas), trabalha com ciclos de entrega que geram scores parciais, os quais compõem o FEE (Fator de Ensino Evolutivo). O desafio foi construir um sistema de informação que apoiasse essa metodologia.

**Solução.** Um sistema em Python que controla turmas, grupos e alunos, ciclos de entrega e scores parciais com feedback do professor. Ele gera relatórios por turma e exporta dados consolidados, com um menu que reúne as funcionalidades.

**Processo.** Foram 4 sprints, de 04/09/2023 a 26/11/2023, com 9 user stories concluídas e 205 commits. A equipe Porygon tinha 8 integrantes: Scrum Master, Product Owner e 6 desenvolvedores. Ferramentas: Python, Git/GitHub, VS Code, Trello, Canva, Excel e Teams.

**Minha contribuição:** Atuei como desenvolvedor da equipe, sem assumir os papéis de Product Owner ou de Scrum Master, com contribuições gerais de desenvolvimento e ajuda na organização das tarefas.

**Aprendizados:** Trabalho em equipe com Scrum, Git e GitHub, divisão de tarefas e integração do código.

---

## 2º semestre: Leitor-de-clima (2024-1)

**Desafio.** Dados climáticos de cidades paulistas estavam dispersos em vários arquivos CSV, um por estação, com formatos variados e valores incorretos.

**Solução.** Um sistema em Java com MySQL e interface em JavaFX que carrega e valida os CSVs e armazena cada variável separadamente. Registros suspeitos (por exemplo, temperatura acima de 60 °C ou abaixo de -20 °C) ficam à parte para revisão manual. O sistema gera relatórios de situação por cidade, de médias por período (com periodicidade horária) e dos elementos para gráficos boxplot.

**Processo.** Foram 4 sprints, de 25/03/2024 a 16/06/2024, e 244 commits. A equipe VCCorp (Vira-lata Caramelo Corp) tinha 8 integrantes. Ferramentas: Java, JavaFX, MySQL, IntelliJ, GitHub e Discord.

**Minha contribuição:** Atuei como desenvolvedor da equipe, sem assumir os papéis de Product Owner ou de Scrum Master, com contribuições gerais de desenvolvimento e ajuda na organização das tarefas.

**Aprendizados:** Trabalho em equipe com Scrum, Git e GitHub, divisão de tarefas e integração do código.

---

## 3º semestre: FATEC-API-3-SEMESTRE (2024-2)

**Desafio.** Desenvolver uma ferramenta web para capturar e armazenar notícias estratégicas de portais e dados de APIs públicas, formando um histórico para análises futuras com IA.

**Solução.** Um sistema com cadastro de portais, APIs, tags e jornalistas, e um processo de web scraping que coleta e armazena os dados. As tags podem ser relacionadas a regionalismos, e há telas de consulta de notícias e de APIs com filtros. Os requisitos não funcionais incluíam grande volume de dados, software livre, manual do usuário, guia de instalação e documentação da API com OpenID.

**Processo.** Foram 4 sprints, de 09/09/2024 a 01/12/2024, com Feira de Soluções em 12/12/2024. As 14 user stories foram realizadas, com 242 commits. A equipe Cerberus tinha 7 integrantes. O projeto usou Kanban no GitHub Projects, burndown e commits no padrão gitmoji.

**Minha contribuição:** Atuei como desenvolvedor da equipe, sem assumir os papéis de Product Owner ou de Scrum Master, com contribuições gerais de desenvolvimento e ajuda na organização das tarefas.

**Aprendizados:** Trabalho em equipe com Scrum, Git e GitHub, divisão de tarefas e integração do código.

---

## 4º semestre: CaramelStray-Api-4Semestre (2026-1), API de destaque

**Desafio.** A empresa parceira, a Altave, opera cerca de 100 sistemas no mundo, cada um exigindo manutenção periódica conforme as horas de uso. A duração do atendimento varia com a localização (um dia no Rio de Janeiro, mais tempo na Ásia), o que complica o planejamento.

**Solução.** Um Sistema de Gestão de Manutenções que centraliza clientes, sistemas, contratos, ativos e técnicos. Ele planeja e registra ordens de manutenção com base nas horas de uso, organiza viagens e checklists e oferece dashboard, histórico e relatórios de prazos e SLAs. Isso permite priorizar atendimentos e evitar atrasos contratuais.

**Tecnologias.** Java e Spring Boot no back-end, Vue com JavaScript e TypeScript no front-end, PostgreSQL como banco, autenticação com JWT, protótipos no Figma, versionamento com Git/GitHub e Docker Compose.

### Gestão do projeto

O backlog tem 19 user stories priorizadas e estimadas, distribuídas em 3 sprints:

- **Sprint 1 (16/03 a 05/04):** cadastros base e criação de ordens de manutenção.
- **Sprint 2 (13/04 a 03/05):** execução, criticidade, viagens, histórico, checklists e relatório de manutenções vencidas.
- **Sprint 3 (11/05 a 31/05):** dashboard, calendário de técnicos e visualização no mapa.

O projeto adotou DoR e DoD por sprint, burndown, padrão de branches e commits, manual do usuário e vídeos de acompanhamento. O repositório tem 465 commits. A equipe tem 8 integrantes (PO, Scrum Master e 6 desenvolvedores), e a Feira de Soluções foi em 25/06/2026.

**Minha contribuição:** Desenvolvedor no front-end em Vue: relatório de manutenção, lista de ordens do técnico, cards do dashboard, modal do calendário, lista de embarcações atracadas, modal de preparação de viagem e atualização do mapa (13 commits, de 26/04 a 29/05/2026).

**Resultados e aprendizados:** Todas as histórias das 3 sprints foram entregues, e o produto foi apresentado aos clientes na Feira de Soluções. Aprendi o fluxo de branches e pull requests, o consumo de API REST autenticada e interfaces com calendário, gráficos e mapas.

---

## Autor

Guilherme Bezerra Junqueira ([@GuilhermebJunqueira](https://github.com/GuilhermebJunqueira))
