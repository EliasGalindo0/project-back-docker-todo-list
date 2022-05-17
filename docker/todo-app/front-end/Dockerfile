#- Acesse a pasta `./todo-app/front-end`;
#- Instalar a aplicação utilizando o comando `npm install`;
#- O processo não deve retornar erros. `Warns` *(Avisos)* não impedem seu funcionamento;
#- Rodar a aplicação com `npm start`;
#- Esse aplicativo requer, **excepcionalmente**, um arquivo `.env`, já contido em sua pasta no repositório;
#- Por padrão, essa aplicação funciona a partir da porta `3000`;
#- Essa aplicação pode receber variáveis de ambiente para mudar o acesso do `back-end`:
  #- `REACT_APP_API_HOST`: padrão `localhost`;
    #- *(Docker)* Aqui você deve indicar o nome do container do `back-end`;
  #- `REACT_APP_API_PORT`: padrão `3001`.
    #- *(Docker)* Aqui você deve indicar a porta que você definiu internamente no container do `back-end`;

FROM node:14-alpine
WORKDIR /front-end
COPY . . 
ADD node_modules.tar.gz .
EXPOSE 3000
RUN npm install
