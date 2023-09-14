<p align="center">
    <img alt="Rocketseat Education" src="https://avatars.githubusercontent.com/u/69590972?s=200&v=4" width="100px" />
</p>

<p align="center">Upload.ai é um aplicativo que permite fazer upload de vídeos e, por meio de IA, criar automaticamente títulos e descrições atraentes com boa indexação.</p>

<p align="center">
  <a href="https://github.com/Caique017">
    <img alt="Feito por Caique Nunes" src="https://img.shields.io/badge/made%20by-Caique%20Nunes-blue">
  </a>
</p>

---

## 🧪 Tecnologias

Este projeto foi desenvolvido utilizando as seguintes tecnologias:

- [React + Vite](https://vitejs.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Prisma](https://www.prisma.io/)
- [Openai](https://openai.com/)
- [Shadcn.ui](https://ui.shadcn.com/)
- [Tailwind CSS](https://tailwindcss.com//)

---

## 🚀 Introdução e execução do projeto

```bash
# Clonar o repositório
$ git clone https://github.com/Caique017/Upload-AI

```

### Web

```bash
# Entre no repositório
$ cd web-upload-ai

# Instalar dependências
$ npm i ou npm install

# Execute o aplicação
$ npm run dev
```

### Api

```bash
# Entre no repositório
$ cd api-upload-ai

# Crie um arquivo .env e copie o conteúdo do arquivo .env.example para ele.
# Lembre-se de adicionar sua API_KEY do openai

# Crie uma pasta tmp, onde os arquivos de áudio serão armazenados

#Instala dependências
$ npm i ou npm install

# Execute o arquivo seed.ts para preencher os prompts
$ npx prisma db seed

# Rode a aplicação
$ npm run dev
```