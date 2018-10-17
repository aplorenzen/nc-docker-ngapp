FROM node
WORKDIR /usr/src/app
RUN npm install -g @angular/cli@latest
ENTRYPOINT bash -c "ng build --prod --build-optimizer"
