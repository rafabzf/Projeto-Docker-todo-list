FROM node:14 AS todofrontend

WORKDIR /todo-app/frontend

EXPOSE 3000

ADD node_modules.tar.gz .

COPY . .

CMD ["npm", "start"]