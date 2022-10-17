FROM mjgargani/puppeteer:trybe1.0
ADD node_modules.tar.gz /todo-app/tests
COPY . /todo-app/tests
WORKDIR /todo-app/tests
CMD ["npm", "test"]
