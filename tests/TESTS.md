# 🧪 Plano de Testes de Software

Este plano visa garantir que as entregas do HelpingHub estejam em conformidade com os critérios de aceitação definidos pelo Product Owner.

## 1. Pirâmide de Testes

O projeto utiliza a pirâmide de testes para garantir cobertura eficiente.

1.  **Unitários (60%):** Testes de lógica pura (ex: validador de e-mail, formatador de datas).
2.  **Integração (30%):** Testes de integração com o banco de dados e rotas da API.
3.  **E2E (10%):** Testes de fluxo completo de usuário no navegador.

### 1.1. Testes Unitários
* **Ferramenta:** Jest.
* **Objetivo:** Validar funções de lógica de negócio e validações de dados no Backend.

### 1.2. Testes de Integração
* **Ferramenta:** Supertest.
* **Objetivo:** Garantir a comunicação correta entre as rotas da API e o banco MySQL.

### 1.3. Testes de UI / Aceitação
* **Ferramenta:** Cypress / Teste Manual.
* **Objetivo:** Validar fluxos de ponta a ponta (E2E) conforme o protótipo da Bianca.

## 2. Roteiro de Testes Manuais (QA)

Responsável: @Guixdreyk | Guilherme Santos Moreira

| Passo | Ação | Resultado Esperado |
| :--- | :--- | :--- |
| 1 | Tentar criar ticket sem descrição. | Sistema exibe alerta: "Campo obrigatório". |
| 2 | Técnico clica em "Assumir Chamado". | Status muda para "Em Atendimento" e cor do card muda para Azul. |
| 3 | Usuário tenta acessar rota `/admin` sem permissão. | Sistema redireciona para `/dashboard` com erro 403. |