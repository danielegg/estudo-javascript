# Lista de Tarefas - Anotações

# Passos iniciais

1. Criando aplicação React
   npx create-react-app .
1.1 Instalando no node_modules quando não existir no projeto
   npm install
2. Iniciar a aplicação
   npm start (dentro do diretório da aplicação)
3. Limpar arquivos desnecessários criado pelo create-react-app.
4. Configuração ESLint e Editorconfig

    4.1. Editorconfig
    No VS Code instale a extensão EditorConfig for VS Code
    Clique com o botão direito no diretório da aplicação, depois em Generate .editorconfig

    4.2 ESLint
    No terminal digite:

    - npm i eslint babel-eslint --save-dev
    - npx eslint --init
      -- To check syntax, find problems, and enforce code style
      -- JavaScript modules (import/export)
      -- React
      -- Does your project use TypeScript? No
      -- Browser
      -- Use a popular style guide
      -- Airbnb: https://github.com/airbnb/javascript
      -- JavaScript
      -- Would you like to install them now with npm? Yes
    - Edit o arquivo gerado .eslintrc.js
      -- parser: 'babel-eslint',
