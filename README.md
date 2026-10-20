# Portfólio de Aprendizagem de Projetos Integrados (API)

Trabalho de Graduação (TG), modelo Portfólio, do curso de Banco de Dados da Fatec Professor Jessen Vidal (São José dos Campos).

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

**Minha contribuição:** Desenvolvedor (sem ser PO ou Scrum Master), com foco na interação com o usuário. Criei o menu do sistema (busca de professor por login e senha, consulta de turmas e alunos, notas, pesos e médias) sobre a planilha de dados e escrevi funções do sistema de notas (criação das abas de notas e de turmas, listagem de turmas). Também ajudei a organizar as tarefas da equipe.

**Aprendizados:** Lógica de programação em Python (funções, laços, condicionais, entrada e saída, tratamento de login ou aluno não encontrado); leitura e escrita de planilhas com openpyxl como base de dados; regras de negócio como cadastro de turmas, notas, pesos e médias; organização do programa em menu com funções separadas; trabalho em equipe de 8 pessoas com sprints, user stories, Trello e Teams; e primeiro uso de Git e GitHub, com integração da parte de cada integrante.

**Evidências:** commits [1a766fc](https://github.com/Porygon-Users/API-Porygon/commit/1a766fc) (menu) e [675ddf0](https://github.com/Porygon-Users/API-Porygon/commit/675ddf0) (sistema de notas).
---

## 2º semestre: Leitor-de-clima (2024-1)

**Desafio.** Dados climáticos de cidades paulistas estavam dispersos em vários arquivos CSV, um por estação, com formatos variados e valores incorretos.

**Solução.** Um sistema em Java com MySQL e interface em JavaFX que carrega e valida os CSVs e armazena cada variável separadamente. Registros suspeitos (por exemplo, temperatura acima de 60 °C ou abaixo de -20 °C) ficam à parte para revisão manual. O sistema gera relatórios de situação por cidade, de médias por período (com periodicidade horária) e dos elementos para gráficos boxplot.

**Processo.** Foram 4 sprints, de 25/03/2024 a 16/06/2024, e 244 commits. A equipe VCCorp (Vira-lata Caramelo Corp) tinha 8 integrantes. Ferramentas: Java, JavaFX, MySQL, IntelliJ, GitHub e Discord.

**Minha contribuição:** Desenvolvedor (sem ser PO ou Scrum Master). Comecei no front-end em JavaFX e, da metade para o final, foquei no back-end. Fiz as telas de parâmetros suspeitos, de cidade e de estação (FXML e controladores) e reescrevi a classe `DbUtils`, que concentra o acesso ao MySQL.

**Aprendizados:** Interfaces em JavaFX, separando telas (FXML) e lógica (controladores); tratamento de eventos e de mensagens de erro ao usuário; ligação com o MySQL por classe utilitária, consultas e inserções a partir do Java e redução de código repetido; caminho dos dados validados, como valores suspeitos, do CSV até a tela e o relatório; branch por sprint, merges, conflitos e revisão de código; e visão do fluxo completo, da tela ao banco.

**Evidências:** [e19afbd](https://github.com/VCCorpTeam/Leitor-de-clima/commit/e19afbd) (parâmetros), 83e66dd (cidade e estação) e [c2b51ca](https://github.com/VCCorpTeam/Leitor-de-clima/commit/c2b51ca) (DbUtils).
---

## 3º semestre: FATEC-API-3-SEMESTRE (2024-2)

**Desafio.** Desenvolver uma ferramenta web para capturar e armazenar notícias estratégicas de portais e dados de APIs públicas, formando um histórico para análises futuras com IA.

**Solução.** Um sistema com cadastro de portais, APIs, tags e jornalistas, e um processo de web scraping que coleta e armazena os dados. As tags podem ser relacionadas a regionalismos, e há telas de consulta de notícias e de APIs com filtros. Os requisitos não funcionais incluíam grande volume de dados, software livre, manual do usuário, guia de instalação e documentação da API com OpenID.

**Processo.** Foram 4 sprints, de 09/09/2024 a 01/12/2024, com Feira de Soluções em 12/12/2024. As 14 user stories foram realizadas, com 242 commits. A equipe Cerberus tinha 7 integrantes. O projeto usou Kanban no GitHub Projects, burndown e commits no padrão gitmoji.

**Minha contribuição:** Desenvolvedor (sem ser PO ou Scrum Master). Tarefas de front-end em Vue e o back-end em Java correspondente. Implementei a edição de regionalismos (US06: `RegionalismoView.vue`, modal de edição, `RegionalismoController`, repositório e entidade), os modais de edição de tag, portal e API, a configuração de CORS e a padronização do CSS (cerca de 1.450 linhas).

**Aprendizados:** Vue e TypeScript no front-end, back-end em Java, comunicação por API REST e CORS, Kanban, branches por história de usuário, pull requests e padronização visual.

**Evidências:** [8350612](https://github.com/c137santos/FATEC-API-3-SEMESTRE/commit/8350612) (edição de regionalismo) e [9258019](https://github.com/c137santos/FATEC-API-3-SEMESTRE/commit/9258019) (CSS).
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

**Minha contribuição:** Desenvolvedor no front-end em Vue, com algumas tarefas que também envolveram o back-end: relatório de manutenção, lista de ordens do técnico, cards do dashboard, modal do calendário, embarcações atracadas, preparação de viagem e polling com status no mapa; ajustes de rotas e da barra lateral e pequenas mudanças em DTOs, repositório de ativos e serviço de técnicos.

**Aprendizados:** Estudo de Vue (componentes, rotas, estado e consumo de API), fluxo de feature/fix com pull requests e resolução de conflitos, API REST protegida por JWT, bibliotecas de calendário e mapa e integração entre front-end e back-end. Na Feira de Soluções, apresentei o produto aos clientes e treinei formas de explicá-lo a quem não é da área técnica.

**Evidências:** [c6735dd](https://github.com/CaramelStray/CaramelStray-Api-4Semestre/commit/c6735dd) (relatório), c196215 (dashboard) e [f441e6b](https://github.com/CaramelStray/CaramelStray-Api-4Semestre/commit/f441e6b) (mapa).
---

## Autor

Guilherme Bezerra Junqueira ([@GuilhermebJunqueira](https://github.com/GuilhermebJunqueira))
