FROM node:8-alpine
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY . .
ENV PATH /usr/src/app/node_modules/.bin:$PATH
RUN npm install
RUN npm install -g @angular/cli
EXPOSE 4200
CMD ng serve --host 0.0.0.0