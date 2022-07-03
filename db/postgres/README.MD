## Criar novo usuario com permissões sobre um database

```
create database mydb;
create user myuser with encrypted password 'mypass';
grant all privileges on database mydb to myuser;

-- USE database
GRANT ALL PRIVILEGES ON ALL TABLES IN SCHEMA public TO myuser;
GRANT ALL PRIVILEGES ON ALL SEQUENCES IN SCHEMA public TO myuser;
GRANT ALL PRIVILEGES ON ALL FUNCTIONS IN SCHEMA public TO myuser;
```
