# My Web Components 🚀

Uma biblioteca de Web Components nativos, encapsulados e reutilizáveis, desenvolvida para ecossistemas modernos 
de alta performance. Este repositório centraliza componentes de interface que atendem de forma perfeitamente
os projetos da nossa stack principal: **Laravel 13, Vue.js, Inertia.js e Tailwind CSS**.

---

## 💡 Por que Web Components?

Ao adotar a especificação nativa do ecossistema Web (Custom Elements, Shadow DOM e HTML Templates), garantimos:
* **Independência de Framework:** Os componentes funcionam nativamente no HTML do Laravel (Blade), dentro de views Vue.js (via Inertia) ou em qualquer outra tecnologia.
* **Isolamento de Escopo (Shadow DOM):** Estilos internos não vazam para a aplicação principal e vice-versa, evitando conflitos de CSS.
* **Compatibilidade com Tailwind CSS:** Estruturados para aceitar diretrizes de estilização utilitária e propriedades customizadas (`CSS Variables`) para fácil tematização.

---

## 🛠 Tecnologias e Padrões Utilizados

* **Linguagem:** JavaScript (ES6+)
* **Web Standards:** Custom Elements API, Shadow DOM, HTML Templates
* **Estilização:** Tailwind CSS & CSS Custom Properties (Variáveis CSS)
* **Ecossistema Alvo:** Laravel 13, Vue.js 3, Inertia.js

<!--

## 📁 Estrutura do Repositório

```text
my-web-components/
├── src/
│   ├── components/
│   │   ├── custom-button/
│   │   │   ├── custom-button.js
│   │   │   └── custom-button.css
│   │   └── custom-modal/
│   │       ├── custom-modal.js
│   │       └── custom-modal.css
│   └── index.js          # Main entry point para exportação dos componentes
├── demo/                 # Ambiente de testes isolado
│   ├── index.html
│   └── app.js
├── package.json
└── README.md
-->
