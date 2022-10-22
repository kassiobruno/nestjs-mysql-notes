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
<img src="https://user-images.githubusercontent.com/61987467/197354227-24fec1cc-6361-4b70-af3a-64ad23122fb5.png"><img>
</span>

<span align="center">
<img src="https://user-images.githubusercontent.com/61987467/197354229-067fb1dc-7dc4-4d16-aee6-2286d2b5f53d.png"><img>
</span>

<span align="center">
<img src="https://user-images.githubusercontent.com/61987467/197354230-4cf5f7b0-bc44-4aba-9c6b-d1eb8830c20c.png"><img>
</span>

<span align="center">
<img src="https://user-images.githubusercontent.com/61987467/197354231-52bb14b1-47ae-4e3c-a1dd-0689b37b3918.png"><img>
</span>
