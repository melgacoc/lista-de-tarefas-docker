FROM node:14-alpine
EXPOSE 3001
RUN mkdir -p /todo-app/back-end
ADD node_modules.tar.gz /todo-app/back-end
COPY . /todo-app/back-end
WORKDIR /todo-app/back-end
CMD ["npm", "start"]

