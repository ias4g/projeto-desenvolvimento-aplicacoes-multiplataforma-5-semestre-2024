<img src=".github/tela-aplicacao-web.png"/>

# Monorepo Speech4Text

## Visão Geral

Este monorepo contém dois projetos principais: o backend (`speech4text-backend`) e o frontend (`speech4text-ai-front`) para a aplicação Speech4Text. A aplicação Speech4Text utiliza IA para converter fala em texto, fornecendo uma interface amigável para os usuários.

## Projetos

### 1. speech4text-backend

#### Descrição
O serviço de backend é construído com Fastify, Prisma e TypeScript. Ele lida com requisições API, gerencia interações com o banco de dados e integra-se com a API OpenAI para funcionalidades impulsionadas por IA.

#### Instalação

1. Clone o repositório e navegue até o diretório do backend:
   ```bash
   git clone <url_do_repositorio>
   cd speech4text-backend
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

#### Scripts

- **Desenvolvimento**: Inicie o servidor de desenvolvimento com recarregamento automático.
  ```bash
  npm run dev
  ```

- **Seed do Banco de Dados**: Execute o script de seed do Prisma para popular o banco de dados com dados iniciais.
  ```bash
  npx prisma db seed
  ```

#### Dependências

- `@fastify/cors`: Suporte a CORS para Fastify.
- `@fastify/multipart`: Manipulação de multipart para Fastify.
- `@prisma/client`: Cliente Prisma para interações com o banco de dados.
- `ai`: Integração de funcionalidades de IA.
- `fastify`: Framework web rápido e de baixa sobrecarga.
- `openai`: Cliente da API OpenAI.
- `zod`: Validação de esquemas com TypeScript.

#### Dependências de Desenvolvimento

- `@types/node`: Definições de TypeScript para Node.js.
- `prisma`: ORM para esquema de banco de dados e migrações.
- `tsx`: Motor de execução de TypeScript.
- `typescript`: Suporte à linguagem TypeScript.

### 2. speech4text-ai-front

#### Descrição
O frontend é construído com React, Vite e TailwindCSS. Ele fornece uma interface moderna e responsiva para os usuários interagirem com a aplicação Speech4Text.

#### Instalação

1. Clone o repositório e navegue até o diretório do frontend:
   ```bash
   git clone <url_do_repositorio>
   cd speech4text-ai-front
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

#### Scripts

- **Desenvolvimento**: Inicie o servidor de desenvolvimento do Vite.
  ```bash
  npm run dev
  ```

- **Build**: Compile o projeto para produção.
  ```bash
  npm run build
  ```

- **Preview**: Visualize a build de produção localmente.
  ```bash
  npm run preview
  ```

#### Dependências

- `@ffmpeg/ffmpeg`: Integração com FFmpeg para processamento de vídeo.
- `@phosphor-icons/react`: Ícones Phosphor para React.
- `@radix-ui/react-*`: Componentes Radix UI para React.
- `ai`: Integração de funcionalidades de IA.
- `axios`: Cliente HTTP para requisições API.
- `class-variance-authority`: Utilitário para gerenciar nomes de classes condicionais.
- `clsx`: Utilitário para construir strings de `className`.
- `react`: Biblioteca React.
- `react-dom`: Ligações do React DOM.
- `tailwind-merge`: Utilitário para mesclar classes do Tailwind CSS.
- `tailwindcss-animate`: Animações do Tailwind CSS.

#### Dependências de Desenvolvimento

- `@types/node`: Definições de TypeScript para Node.js.
- `@types/react`: Definições de TypeScript para React.
- `@types/react-dom`: Definições de TypeScript para React DOM.
- `@vitejs/plugin-react`: Plugin Vite para React.
- `autoprefixer`: Plugin PostCSS para adicionar prefixos de fornecedor ao CSS.
- `postcss`: Ferramenta para transformar CSS.
- `tailwindcss`: Framework CSS de utilitários.
- `typescript`: Suporte à linguagem TypeScript.
- `vite`: Ferramentas de frontend para projetos web modernos.

## Contribuindo

Contribuições para melhorar a aplicação Speech4Text são bem-vindas. Para contribuir, siga estes passos:

1. Faça um fork do repositório.
2. Crie uma nova branch (`git checkout -b feature/sua-feature`).
3. Faça suas alterações.
4. Commit suas alterações (`git commit -am 'Adicionar nova feature'`).
5. Faça push para a branch (`git push origin feature/sua-feature`).
6. Crie um novo Pull Request.

## Licença

Este projeto está licenciado sob a licença ISC.

## Autores

Este projeto é mantido pela equipe do Speech4Text. Contribuições da comunidade são bem-vindas e encorajadas.