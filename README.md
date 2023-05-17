# Clone do Messenger em tempo real: Next.js 13, React, Tailwind, Prisma, MongoDB, NextAuth, Pusher

![Copy of Copy of Fullstack Twitter Clone (1)](https://user-images.githubusercontent.com/23248726/236631198-90414da5-ee43-46a9-8898-70b003bcd83d.png)

Características principais:

- Mensagens em tempo real usando Pusher
- Notificações e alertas de mensagens
- Design Tailwind para interface de usuário elegante
- Animações Tailwind e efeitos de transição
- Capacidade de resposta total para todos os dispositivos
- Autenticação de credenciais com NextAuth
- Integração de autenticação do Google
- Integração de autenticação Github
- Upload de arquivos e imagens usando Cloudinary CDN
- Validação e manipulação de formulários de cliente usando react-hook-form
- Tratamento de erros do servidor com react-toast
- Recibos de leitura de mensagens
- Status do usuário online/offline
- Bate-papos em grupo e mensagens individuais
- Anexos de mensagens e compartilhamento de arquivos
- Personalização e configurações do perfil do usuário
- Manipulação de relações entre componentes Servidor e Filho em um ambiente de tempo real
- Criação e gerenciamento de salas de bate-papo e canais

### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone https://github.com/jooaogbriel/messenger.git
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
DATABASE_URL=
NEXTAUTH_SECRET=

NEXT_PUBLIC_PUSHER_APP_KEY=
PUSHER_APP_ID=
PUSHER_SECRET=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=

GITHUB_ID=
GITHUB_SECRET=

GOOGLE_CLIENT_ID=
GOOGLE_CLIENT_SECRET=
```

### Setup Prisma

```shell
npx prisma db push

```

### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |
