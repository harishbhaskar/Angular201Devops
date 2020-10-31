FROM node:12.0        
WORKDIR /usr/src/
RUN npm install -g @angular/cli@        
COPY . /usr/src/               
RUN npm install
CMD ng serve --host 0.0.0.0 --port 4200
