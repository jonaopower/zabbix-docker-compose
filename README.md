# Ambiente Zabbix com Docker Compose

_TLDR_;
Clonar repo:
git clone https://github.com/jonaopower/zabbix-docker-compose.git

Editar arquivo "docker-compose.yml" e modificar caminho absoluto do volume montado para persistencia de dados do banco mysql

```Dockerfile
    volumes:
      - /Users/jonas/Coding/zabbix/docker-comnpose2/mysql-data:/var/lib/mysql
```

Se desejar, alterar tag das imagens com versao especifica.

docker-compose up -d
