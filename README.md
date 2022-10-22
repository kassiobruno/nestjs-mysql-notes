# Projeto NestJs MySQL

Antes de ser inicializado o projeto, é necessário ajustar a conexão com o banco de dados mySQL, alterando o "username", "password" e "port" no arquivo "ormconfig.json" para o banco mySQL que será utilizado.
```
{
    "type": "mysql",
    "host": "localhost",
    "port": 6603,
    "username": "root",
    "password": "123",
    "database": "noteapp",
    "entities": ["dist/**/*.entity{.ts,.js}"],
    "synchronize": true
}
```
Então instale as dependencias necessárias com o comando abaixo:
```
npm install
```
e para executar o projeto:
```
npm run start:dev
```
<span align="center">
![dbeaver]
</span>

<span align="center">
![dockermysql]
</span>

<span align="center">
![get_notes]
</span>

<span align="center">
![insert_note]
</span>
