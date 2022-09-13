## Autenticação e autorização - Ignite
Esta aplicação foi desenvolvida no módulo de autenticação e autorização do ignite. O objetivo dessa aplicação é utilizar mecanismos de autenticação com [JWT](https://jwt.io) (JSON Web Token) e autorizações com perfil e permissões.
O armazenamentos das informações foi utilizado através dos cookies, que por sua vez, elas podem ser acessadas através do client-side e server-side.

Link da API utilizada: https://github.com/rocketseat-education/ignite-reactjs-auth-backend


### Conceitos e técnicas utilizadas

- [ReactJS](https://pt-br.reactjs.org)
- [React Hooks](https://pt-br.reactjs.org/docs/hooks-intro.html)
- [NextJS](https://nextjs.org/)
- [Typescript](https://www.typescriptlang.org)
- [Yarn](https://classic.yarnpkg.com/en/)
- [axios](https://axios-http.com)
- [cookies](https://developer.mozilla.org/en-US/docs/Web/API/Document/cookie)
- [nookies](https://github.com/maticzav/nookies)
- [JWT](https://jwt.io)

### Rodar aplicação

### Instalação das dependências listadas no arquivo package.json

```console
$ yarn
```

#### Execução da aplicação front-end local.

Inicia um servidor local front-end no endereço [http://localhost:3000](http://localhost:3000) no browser.
```console
$ yarn dev
```

#### Build e gerar os arquivos estáticos (SSG).

Gera uma build e os arquivos estáticos que foram configurados usando o SSG.

```console
$ yarn build
```

#### Execução da aplicação a partir build gerada.

Inicia um servidor local front-end no endereço [http://localhost:3000](http://localhost:3000) no browser.
```console
$ yarn start
```
