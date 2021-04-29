FROM node

WORKDIR /usr/app

COPY package.json ./

RUN npm install

COPY . . 
# Caso seja em produção descomente a linha a baixo
#RUN npm run build

EXPOSE 3000 
# Caso seja em produção troque dev por start
CMD ["npm", "run", "dev"]