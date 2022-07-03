## Criar novo usuario com permissões sobre um database

```
create database mydb;
create user myuser with encrypted password 'mypass';
grant all privileges on database mydb to myuser;
```
