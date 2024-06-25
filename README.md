# Plataforma de Cursos

Este projeto é uma plataforma de cursos online desenvolvida utilizando HTML, CSS e Tailwind CSS. A estrutura do projeto foi organizada para facilitar a manutenção e a escalabilidade do código.

## Estrutura do Projeto

A estrutura de pastas e arquivos do projeto é a seguinte:

```
FIAP-PLATFORM/
├── app/
│   └── index.html
├── assets/
│   ├── fonts/
│   ├── imgs/
│   ├── svgs/
│   └── favicon.ico
├── css/
│   ├── global.css
│   └── tailwind.css
├── node_modules/
├── .gitignore
├── package-lock.json
├── package.json
├── README.md
└── tailwind.config.js
```

- `app/index.html`: Arquivo principal HTML da aplicação.
- `assets/`: Pasta contendo fontes, imagens e ícones SVG utilizados na aplicação.
- `css/`: Pasta contendo os arquivos CSS.
  - `global.css`: Estilos globais da aplicação.
  - `tailwind.css`: Arquivo gerado pelo Tailwind CSS.
- `node_modules/`: Pasta contendo os módulos Node.js instalados.
- `.gitignore`: Arquivo que especifica quais arquivos e pastas devem ser ignorados pelo Git.
- `package-lock.json`: Arquivo que registra a árvore exata de dependências instaladas.
- `package.json`: Arquivo de configuração do projeto Node.js, incluindo as dependências.
- `README.md`: Documentação do projeto.
- `tailwind.config.js`: Arquivo de configuração do Tailwind CSS.

## Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:

- [Node.js](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/)

## Instalação e Execução

Para instalar as dependências do projeto e iniciar o desenvolvimento com Tailwind CSS, execute os seguintes comandos na raiz do projeto:

```bash
# Instale as dependências do projeto
npm install

# Compile os estilos do Tailwind CSS e assista as mudanças nos arquivos CSS
npx tailwindcss -i ./css/tailwind.css -o ./css/global.css --watch
```

## Configuração do Tailwind CSS

O arquivo `tailwind.config.js` é utilizado para configurar o Tailwind CSS conforme as necessidades do projeto. Você pode personalizar as configurações de cores, espaçamento, fontes, entre outros, editando este arquivo.


## Contato

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato.

---

Desenvolvido com ♥ por [Ingrydh Potter].
