# Evolupa Frontend

Frontend da plataforma.

## Repositórios relacionados

### Backend (API)
https://github.com/F3rCar/evolupa-api

## Tecnologias

- HTML
- CSS
- JavaScript

## Instalação

Clone o repositório:

```bash
git clone <https://github.com/F3rCar/evolupa-web.git>
```

Instale as dependências:

```bash
npm install
```


E basta abrir o projeto ou utilizar Live Server.

## Comunicação

A aplicação consome a API em:

http://localhost:5000

## Convenções

- Manter a organização das pastas.
- Evitar repetição de código.
- Toda requisição deve passar pela pasta `js/api`.

## Estrutura

```text
evolupa-front/
│
├── assets/
│   ├── images/
│   └── icons/
│
├── css/
│   ├── global.css
│   ├── variables.css
│   ├── components.css
│   └── pages/
│       ├── login.css
│       ├── cadastro.css
│       ├── perfil.css
│       ├── atividades.css
│       ├── historias.css
│       ├── dashboard.css
│       └── admin.css
│
├── js/
│   ├── api/
│   ├── components/
│   ├── pages/
│   └── utils/
│
├── pages/
│   ├── index.html
│   ├── login.html
│   ├── cadastro.html
│   ├── perfil.html
│   ├── atividades.html
│   ├── historias.html
│   ├── dashboard.html
│   └── admin/
│       ├── dashboard.html
│       ├── atividades.html
│       ├── historias.html
│       ├── pdfs.html
│       ├── videos.html
│       └── usuarios.html
│
├── .gitignore
├── eslint.config.js
├── .prettierrc
├── package.json
├── package-lock.json
└── README.md
```

## Organização

### 📄 pages/
Contém todos os arquivos HTML da aplicação.

### 🎨 css/
Contém todos os estilos do projeto.

- `global.css` → estilos globais.
- `variables.css` → cores, fontes e variáveis.
- `components.css` → estilos de componentes reutilizáveis.
- `pages/` → estilos específicos de cada página.

### ⚙️ js/
Contém todo o JavaScript do projeto.

- `api/` → comunicação com a API.
- `components/` → componentes reutilizáveis.
- `pages/` → lógica de cada página.
- `utils/` → funções auxiliares.

### 🖼️ assets/
Arquivos estáticos.

- `images/` → imagens.
- `icons/` → ícones.

