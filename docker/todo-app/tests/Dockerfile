FROM mjgargani/puppeteer:trybe1.0
WORKDIR /todo-app/tests
ADD node_modules.tar.gz /todo-app/tests
COPY . /todo-app/tests
CMD ["npm", "test"]
