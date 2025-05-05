# Portfólio Web com JavaScript, GitHub Codespaces e Copilot

Este projeto é uma aplicação web de portfólio pessoal desenvolvida com o objetivo de ajudar você a criar, personalizar e publicar seu próprio site de portfólio de forma rápida e simples. Ele utiliza tecnologias modernas como React e é configurado para funcionar diretamente no navegador usando GitHub Codespaces.

## O que este projeto faz?

- Exibe informações pessoais, como "Sobre mim" e redes sociais.
- Apresenta projetos nos quais você trabalhou, com título, descrição e links.
- Permite personalização de imagens, textos e seções.
- Pode ser publicado na nuvem usando Azure Static Web Apps ou GitHub Pages.

## Tecnologias utilizadas

- **Linguagens**: JavaScript, HTML, CSS.
- **Framework**: React.
- **Ferramentas**:
  - [Parcel](https://parceljs.org/) para empacotamento e construção.
  - [ESLint](https://eslint.org/) e [Prettier](https://prettier.io/) para qualidade e formatação de código.
  - [GitHub Codespaces](https://github.com/features/codespaces/) para desenvolvimento no navegador.
  - [GitHub Copilot](https://copilot.github.com) para sugestões de código.

## Como fazer funcionar?

1. **Crie um Codespace**:
   - Clique no botão **"Use this Template"** no repositório e crie um novo repositório.
   - Na aba **Codespaces**, selecione **"Create codespace on main"**.

2. **Instale as dependências**:
   - No terminal do Codespace, execute:
     ```bash
     npm install
     ```

3. **Inicie o servidor de desenvolvimento**:
   - Execute:
     ```bash
     npm run start
     ```
   - O site será iniciado no navegador no endereço `http://localhost:1234`.

4. **Personalize o site**:
   - Edite os arquivos em [Components](http://_vscodecontentref_/0) para atualizar informações como "Sobre mim", projetos e imagens.

5. **Publique na nuvem**:
   - Para GitHub Pages:
     - Atualize o campo `homepage` no [package.json](http://_vscodecontentref_/1).
     - Execute:
       ```bash
       npm run deploy
       ```
   - Para Azure Static Web Apps:
     - Configure o serviço no menu Azure do VS Code.

## Recursos adicionais

- [Documentação do React](https://reactjs.org/)
- [Guia do GitHub Codespaces](https://docs.github.com/en/codespaces/guides)
- [Documentação do GitHub Copilot](https://docs.github.com/en/copilot)