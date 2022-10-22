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
![insert_note](/uploads/d678ae837101b6da09bd59a539aecac5/insert_note.png)
</span>

<span align="center">
![get_notes](/uploads/ed25711d208eb4d63d964fe38254e4e5/get_notes.png)
</span>

<span align="center">
![dockermysql](/uploads/22a635fec14baa214567e1b32fe97525/dockermysql.png)
</span>

<span align="center">
![dbeaver](/uploads/86b02eaf7e9fef1ac84b8fb24faed9fb/dbeaver.png)
</span>
