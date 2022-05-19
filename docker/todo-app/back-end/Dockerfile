#- Acesse a pasta `./todo-app/back-end`;
#- Instalar a aplicação utilizando o comando `npm install`;
#- O processo não deve retornar erros. `Warns` *(Avisos)* não impedem seu funcionamento;
#- Rodar a aplicação com `npm start`;
#- Por padrão, essa aplicação funciona a partir da porta `3001`;

FROM node:14-alpine
EXPOSE 3001
WORKDIR /
ADD node_modules.tar.gz ./
COPY . .
CMD [ "npm", "start" ]
