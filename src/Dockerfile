# imagem base
FROM node:18.11.0

#diretório de trabalho
WORKDIR /app

# copia dos arquivos
COPY package*.json ./

# instalação de dependências
RUN npm install

# copia do resto do projeto
COPY . .

# abertura de porta
EXPOSE 8080

# inicia a aplicação
CMD ["node", "server.js"]