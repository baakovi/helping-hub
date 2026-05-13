# HH: HelpingHub 🆘🍜

> Atividade acadêmica desenvolvida pelo 5º Semestre do curso de Ciência da Computação para a disciplina de **Engenharia de Software**.

O **HelpingHub** é um sistema de Help Desk projetado para otimizar a abertura e gestão de chamados de TI. O foco do projeto é aplicar os conceitos de Engenharia de Software através da metodologia ágil **Kanban**, priorizando a entrega contínua e a visibilidade do fluxo de trabalho.

## 👥 Integrantes e Papéis
* @benioreis | **Benjamin Reis**: Tech Lead & Backend
* @baakovi | **Bianca Vitória**: Frontend & UI/UX
* @Guixdreyk | **Guilherme Santos Moreira**: QA / Tester
* @aguiarmilene25-oss | **Milene Cristina**: Fullstack & DevOps
* @CodingWithSamuel | **Samuel Oliveira**: Product Owner & Requisitos
---

## 🎯 O Projeto
O sistema permite que funcionários de uma organização reportem incidentes técnicos, enquanto a equipe de TI gerencia as resoluções através de uma interface centralizada.

### Principais Funcionalidades (MVP)
- **Autenticação Multi-nível:** Acesso diferenciado para Usuários Comuns e Técnicos de TI.
- **Gestão de Chamados:** Criação, edição e visualização de tickets (título, descrição, prioridade e categoria).
- **Ciclo de Vida do Ticket:** Fluxo de status dinâmico (Aberto -> Em Atendimento -> Pendente -> Resolvido).
- **Dashboard de Controle:** Visão geral para o técnico sobre a carga de trabalho atual.

---

## 🚀 Metodologia de Desenvolvimento
Utilizamos o **Kanban** para gerenciar o fluxo de trabalho. Nosso quadro de tarefas está dividido em:

1.  **Backlog:** Ideias e requisitos que ainda serão detalhados.
2.  **To Do (Pronto para Iniciar):** Tarefas com requisitos definidos aguardando desenvolvimento.
3.  **In Progress (Em Desenvolvimento):** Tarefas sendo executadas (WIP Limit: 3).
4.  **Review / Testing:** Validação técnica e testes de qualidade (QA).
5.  **Done (Finalizado):** Funcionalidades testadas, documentadas e integradas.

### Critérios de Qualidade
- **DoR (Definition of Ready):** Uma tarefa só inicia se tiver descrição e critérios de aceitação claros.
- **DoD (Definition of Done):** Uma tarefa só é finalizada se passar pelos testes do QA e code review.

---

## 🛠️ Tecnologias
* **Linguagem:** TypeScript
* **Frontend:** ReactJS
* **Backend:** Express.js + NodeJS
* **Banco de Dados:** MySQL

---

## 📂 Estrutura do Repositório
```text
├── src/            # Código fonte do projeto
├── docs/           # Documentação de Engenharia de Software (Diagramas, Requisitos)
├── tests/          # Casos de teste e scripts de automação
└── README.md       # Documentação principal
```

## 🏗️ Status do Projeto: Parte 2 Concluída
Nesta fase, estruturamos a base de engenharia e o planejamento de qualidade. O foco agora é a implementação do código base seguindo os diagramas definidos.

## 📁 Links Rápidos para Documentação
* [**Requisitos e Qualidade**](docs/DOCUMENTATION.md)
* [**Arquitetura e Modelagem**](src/SOURCE.md)
* [**Estratégia de Testes**](tests/TESTS.md)

## 🎨 Design & Protótipo
O layout do HelpingHub foi planejado para ser intuitivo e moderno. Possui usuários de teste na primeira tela.

* **Figma:** [Acessar Proposta de Design](https://www.figma.com/make/rKdbQ6wITtCuyFwQEjesyA/Design-Proposal-for-HelpingHub?fullscreen=1)

## 🛠️ Stack Tecnológica
* **Frontend:** React, TypeScript, TailwindCSS.
* **Backend:** Node.js, Express, MySQL.
* **DevOps:** Docker (opcional), GitHub Actions.

## 🏃 Como rodar o projeto (Em breve)
```bash
# Clone o repositório
git clone https://github.com/baakovi/helping-hub.git

# Instale as dependências
npm install

# Inicie o desenvolvimento
npm run dev
```