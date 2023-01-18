FROM node:14-alpine
EXPOSE 3001
WORKDIR /todo-app/back-end/
ADD node_modules.tar.gz .
COPY . .
RUN [ "npm", "install" ]
CMD ["npm", "start"]