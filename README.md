<div align="center">

# 🧪 Automação E2E com Cypress

**OrangeHRM**<br>
Page Objects · Comandos customizados · Testes end-to-end

![Cypress](https://img.shields.io/badge/Cypress-2b2b2b?style=for-the-badge&logo=cypress&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Git](https://img.shields.io/badge/Git-FF6B5B?style=for-the-badge&logo=git&logoColor=white)
![Status](https://img.shields.io/badge/status-em%20evolu%C3%A7%C3%A3o-FF6B5B?style=for-the-badge)


[![Testes](https://github.com/anavirezende/Projeto_Bootcamp_QA/actions/workflows/cypress.yml/badge.svg)](https://github.com/anavirezende/Projeto_Bootcamp_QA/actions)


<img src="docs/execucao.gif" alt="Execução dos testes no Cypress" width="700">

[Objetivo](#-objetivo) · [Cenários](#-cenários-cobertos) · [Arquitetura](#️-arquitetura) · [Como executar](#️-como-executar) · [Aprendizados](#-aprendizados)

</div>

---

## 🎯 Objetivo

Projeto de automação de testes end-to-end desenvolvido durante o bootcamp de QA. Ele garante a qualidade dos fluxos principais do sistema por meio de testes automatizados, reduzindo o esforço de regressão manual.

## ✅ Cenários cobertos

<details open>
<summary><b>📋 Ver cenários por funcionalidade</b></summary>

<br>

| Funcionalidade | Cenários automatizados |
|---|---|
| 🔐 **Login** | [ex.: login válido, senha inválida, campos vazios] |
| 💼 **Cadastro de cargos** | [ex.: cadastro com sucesso, campo obrigatório, duplicidade] |
| 👥 **Cadastro de funcionários** | [ex.: cadastro completo, validações de campos] |

</details>

## 🏗️ Arquitetura

```
cypress/
├── e2e/              # specs dos testes
├── support/
│   ├── pages/        # Page Objects
│   └── commands.js   # comandos customizados
└── fixtures/         # massa de dados
```

- **Page Objects:** separam a lógica de interação com a tela da lógica de teste, o que facilita a manutenção.
- **Comandos customizados:** reaproveitam ações repetidas (ex.: `cy.login()`).
- **Fixtures:** organizam a massa de dados fora dos testes.

## 🛠️ Tecnologias

<div align="center">

| Ferramenta | Uso |
|---|---|
| **Cypress** | Automação E2E |
| **JavaScript** | Linguagem dos testes |
| **Node.js / npm** | Ambiente e dependências |
| **Git / GitHub** | Versionamento |

</div>

## ▶️ Como executar

**Pré-requisito:** [Node.js](https://nodejs.org/) instalado.

```bash
# 1. Clonar o repositório
git clone https://github.com/anavirezende/Projeto_Bootcamp_QA.git
cd Projeto_Bootcamp_QA

# 2. Instalar as dependências
npm install

# 3. Rodar os testes
npx cypress open   # modo interativo
npx cypress run    # modo headless
```

## 📚 Aprendizados

- [ex.: aplicação do padrão Page Object na prática]
- [ex.: organização de massa de dados com fixtures]
- [ex.: estratégias para deixar os testes estáveis, evitando esperas fixas]

## 🗺️ Próximos passos

- [ ] Pipeline de CI com GitHub Actions
- [ ] Relatório de testes (Mochawesome)
- [ ] Testes de API

---

<div align="center">

**Ana Vitória Rezende** · QA Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-FF6B5B?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anavirezende)
[![GitHub](https://img.shields.io/badge/GitHub-2b2b2b?style=for-the-badge&logo=github&logoColor=white)](https://github.com/anavirezende)

🌸 *Construindo qualidade um teste de cada vez.*

</div>
