#- ⚠️ Essa aplicação só funciona **se associada a uma rede Docker**;
#- Acesse a pasta `./todo-app/front-end`;
#- Instalar a aplicação utilizando o comando `npm install`;
#- O processo não deve retornar erros. `Warns` *(Avisos)* não impedem seu funcionamento;
#- Rodar a aplicação com `npm test`;
#- Essa aplicação pode receber variáveis de ambiente para mudar o acesso ao front-end:
  #- `FRONT_HOST`: padrão `localhost`;
    #- *(Docker)* Aqui você deve indicar o nome do container do `front-end`;
  #- `FRONT_PORT`: padrão `3000`.
    #- *(Docker)* Aqui você deve indicar a porta que você definiu internamente no container do `front-end`;

FROM node:14-alpine
WORKDIR /
COPY . . 
ADD node_modules.tar.gz .
EXPOSE 3000
ENTRYPOINT [ "npm", "install" ]
