# discoverFundamenNode

## Esse é o inicio dos estudos dos fundamentos de Node.js que está no Discover/Fundamentar/Node.js na Rockeatseat.
## Os estudos do Discover são gratuitos, basta acessar o site e se cadastrar https://rocketseat.com.br/


## Iniciei o projeto criando um servidor para mostrar os console.log no terminal do vscode
## Para fazer o mesmo, caso você queira, segue o passo a passo

- instalar node e yarn na sua máquina
    você pode acessar o link logo abaixo, e na seção Guias terá o link Instalação das ferramentas, lá têm o passo a passo para instalação 
    no windows, linux e macOS

    (https://www.notion.so/Configura-es-do-ambiente-45e12d2ced17465cabbd81dcbd53576d)

- Depois de tudo instalado:
    - iniciei um projeto com:  yarn init -y
    - instalei o package express:  yarn add express
    - instalei o package nodemon:  yarn add nodemon -D
    - fui no arquivo package.json e inseri um script para rodar o servidor.

    "scripts": {
    "dev": "nodemon src/index.js "
  },

  ### Esse scripts vai ficar logo abaixo de "license": "MIT", e acima de   "dependencies": {     "express": "^4.17.2"

### Segue imagem abaixo

<div align="center">
<img src="https://github.com/jonatasolialmeida/discoverFundamenNode/blob/master/images/json.png"/>
</div>

  - depois é só rodar - yarn dev

  ### O nodemon vai cuidar para que toda alteração que você faça no seu código, atualize automaticamente (refresh) sem a necessidade de dar stop e iniciar novamente o servidor

  ### Ah, tambem criei uma pasta src no projeto, e dentro um arquivo index.js com as primeiras configurações para rodar o servidor

  - const express = require("express");
  - const app = express();
  - app.listen(3333);

  ### Exemplo abaixo

  <div align="center">
<img src="https://github.com/jonatasolialmeida/discoverFundamenNode/blob/master/images/index.png"/>
</div>

  ### Todo trecho de código que vc quiser ver rodar no terminal, coloque abaixo de (const app) e acima de (app.listen) e lógico, usando console.log() para isso...
