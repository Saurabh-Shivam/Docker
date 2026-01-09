FROM node

ENV MONGO_DB_USERNAME=admin \
    MONGO_DB_PWD=qwerty

RUN mkdir -p dockerLearn_app

COPY . /dockerLearn_app

# RUN npm install

CMD ["node", "/dockerLearn_app/server.js"]