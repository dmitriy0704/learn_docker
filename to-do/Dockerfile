FROM node
LABEL maintainer dmitriy.folomkin@yandex.ru
RUN git clone -q https://github.com/dmitriy0704/react-app.git
WORKDIR react-app
RUN npm install > /dev/null
EXPOSE 8000
CMD ["npm","start"]