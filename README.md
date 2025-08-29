cat > README.md << 'EOF'
# 🔍 Projeto: GitHub API – Buscando Usuários

Aplicação web desenvolvida em **HTML, CSS e JavaScript**, que consome a **API do GitHub** para buscar usuários pelo nome e exibir informações do perfil junto com seus repositórios públicos.

---

## 🚀 Funcionalidades
- Buscar usuários do GitHub digitando o nome de usuário.
- Exibir:
  - Foto de perfil (avatar).
  - Nome e bio do usuário.
  - Lista dos repositórios públicos (limitado a 10).
- Mensagem de erro quando o usuário não é encontrado.
- Design responsivo.

---

## 🛠️ Tecnologias Utilizadas
- **HTML5**
- **CSS3**
  - Reset CSS
  - Responsividade
- **JavaScript (ES6+)**
  - Fetch API (requisições HTTP)
  - Módulos ES (`import/export`)
- **API do GitHub**
- **Git & GitHub** (versionamento e deploy)

---

## 📂 Estrutura do Projeto

projeto-inicial-fetch-github-api/
│── index.html
│── src/
│ ├── css/
│ │ ├── reset.css
│ │ └── styles.css
│ └── scripts/
│ ├── index.js
│ ├── variables.js
│ ├── objects/
│ │ ├── screen.js
│ │ └── user.js
│ └── services/
│ ├── repositories.js
│ └── user.js
---

## ▶️ Como Executar Localmente
1. Clone este repositório:
   \`\`\`bash
   git clone git@github.com:brunopenna87/projeto-inicial-fetch-github-api.git
   cd projeto-inicial-fetch-github-api
   \`\`\`
2. Abra o arquivo \`index.html\` no navegador.
3. Digite um nome de usuário do GitHub e clique em **Buscar**.

> **Obs.:** o endpoint base está configurado em \`src/scripts/variables.js\`:
> \`\`\`js
> const baseUrl = 'https://api.github.com/users'
> const repositoriesQuantity = 10
> \`\`\`

---

## 🌐 Demo (GitHub Pages)
- URL: **https://brunopenna87.github.io/projeto-inicial-fetch-github-api/**

---

## 📖 Aprendizados
- Consumo de API REST com **Fetch API**.
- Manipulação de DOM e renderização dinâmica.
- Organização em **módulos ES**.
- Boas práticas de versionamento com Git.

---

## 🗺️ Próximos Passos
- Paginação/“carregar mais” repositórios.
- Exibir seguidores/seguindo e principais linguagens.
- Estado de “carregando” e tratamento de erros mais detalhado.
- Testes unitários com Jest.

---

## 🤝 Contribuição
Contribuições são bem-vindas!  
Abra uma **Issue** ou envie um **Pull Request** seguindo boas práticas de commits (Conventional Commits).

---

## 📝 Licença
Este projeto está sob a licença **MIT**.

---

👨‍💻 Desenvolvido por **[Bruno Penna](https://github.com/brunopenna87)**
EOF
