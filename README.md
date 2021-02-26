<h3 align="center">
	BootCamp Gostack - Desafio 10 - GoRestaurant Web
</h3>

</div>
<p align="center">
  Desafio onde se deveria desenvolver um CRUD em React.js de uma aplicação web.
  O GoRestaurant uma aplicação que lista, edita e deleta pratos de comidas
</p>

<p align="center">
  <a href="#gear-como-rodar">Como usar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-tecnologias-usadas-neste-projeto">Tecnologias</a>
</p>

<h3 align="center">
  <img width="559" height="316" src="https://user-images.githubusercontent.com/56983783/106318010-e8a40800-624d-11eb-91dd-54dafc1ff8f9.png" alt="dashboard page image"/>
</h3>

<h3 align="center">
  <img width="559" height="316" src="https://user-images.githubusercontent.com/56983783/106318064-04a7a980-624e-11eb-835f-5598620d677e.png" alt="modal page to add new dish of food"/>
</h3>

## :computer: Tecnologias usadas neste projeto

O projeto está utilizando as seguintes tecnologias:

-  [reactJS](https://pt-br.reactjs.org/)
-  [axios](https://www.npmjs.com/package/axios)
-  [styled-components](https://styled-components.com/)
-  [react-router-dom](https://reactrouter.com/web/guides/quick-start)
-  [typescript](https://www.typescriptlang.org/)
-  [jest](https://jestjs.io/)
-  [json-server](https://www.npmjs.com/package/json-server)
-  [unform](https://github.com/unform/unform)
-  [yup](https://github.com/jquense/yup)
-  [polished](https://polished.js.org/)
-  [react-dropzone](https://react-dropzone.js.org/)
-  [react-icons](https://react-icons.github.io/react-icons/)

## :gear: Como rodar
Para clonar e rodar esse projeto você vai precisar do [Node](https://nodejs.org/en/) do [Yarn](https://yarnpkg.com/) ou do [Npm](https://www.npmjs.com/get-npm) e do [Git](https://git-scm.com/) instalado na sua máquina.

```bash
# Faça o clone deste repositório para qualquer pasta de sua preferencia
$ git clone https://github.com/AlexBitar80/GoRestaurant-Web GoRestaurant-web

# Vá até essa pasta
$ cd GoRestaurant-web

# rode esses comandos para instalar as dependências
$ yarn || npm install

# O projeto está utilizando uma fake API e para executar utilize:
$ yarn json-server server.json -p 3333

# use esses comandos para rodar o Projeto
$ yarn start || npm run start

# use esses comandos para rodar os testes
$ yarn test || npm run test
```

por padrão assim que rodar o comando para iniciar, o projeto estará rodando em (http://localhost:3000)
