# Graylog install
- generate your graylog admin password web ui by genpassword.sh default: admin/admin
- edit .env for your GRAYLOG_ROOT_PASSWORD_SHA2, GRAYLOG_PASSWORD_SECRET and GRAYLOG_HTTP_EXTERNAL_URI
```
https://docs.graylog.org/en/4.1/pages/configuration/elasticsearch.html
```
## start container
```shell
    docker-compose up -d
```
## Clear Container 
```shell
    docker-compose stop && docker-compose rm
```