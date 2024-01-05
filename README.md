INSTRUÇÕES 
Instalar todas as dependencias indicada pelo package.json
### npm install

Criar variável de ambiente para conectar ao banco de dados com (.env)
### touch .env

Criar base de dados no Mysql
### CREATE DATABASE name_db CHARACTER SET utf8mb4 COLLATE utf8mb4_unicode_ci;

Executar as migrations
### npx sequelize-cli db:migrate

Executar as seeders
### npx sequelize-cli db:seed:all

Iniciar o serviço
### nodemon app.js