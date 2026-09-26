# Dogs

Dogs é uma rede social para compartilhar fotos de cachorros. Este projeto foi desenvolvido como projeto final do [curso React Completo, da Origamid](https://www.origamid.com/curso/react-completo/), que ensina a criar uma aplicação de rede social com React.

O projeto reúne os conceitos praticados no curso, como componentes, hooks, React Router, Context API, formulários, consumo de API e CSS Modules. A aplicação se conecta à API Dogs da Origamid para autenticação e gerenciamento das fotos.

## Funcionalidades

- Visualizar o feed de fotos e abrir os detalhes de cada publicação.
- Criar uma conta, entrar e recuperar a senha.
- Publicar fotos, comentar e excluir as próprias publicações.
- Acessar perfil e estatísticas do usuário.
- Navegar por rotas protegidas após autenticação.

## Tecnologias

- React 18
- React Router
- Vite
- CSS Modules
- Victory, para gráficos
- API Dogs da Origamid

## Executar localmente

Requisitos: Node.js e npm.

```bash
git clone https://github.com/alan-ssantos/origamid-react-dogs.git
cd origamid-react-dogs
npm install
npm run dev
```

O Vite mostrará no terminal o endereço local para abrir no navegador. Para gerar e visualizar a versão de produção:

```bash
npm run build
npm run preview
```

## Publicação

O GitHub Actions gera o build e publica o site no GitHub Pages a cada push na branch `main`. Pull requests executam o build sem publicar. Para habilitar a publicação no repositório, selecione **Settings → Pages → Build and deployment → GitHub Actions**.
