# Домашнее задание к занятию «ELK»
# Козлов Станислав

## Задание 1. Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

![image](https://github.com/stkv1/elk/assets/145263196/c9cc47e1-3125-48ea-9742-04601084dd5e)

## Задание 2. Kibana
Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

![image](https://github.com/stkv1/elk/assets/145263196/bf513004-e6e8-4ff7-b653-ebbbe053e82e)


## Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

![image](https://github.com/stkv1/elk/assets/145263196/a231e4ea-62b6-4c6e-90db-7392e03d82b8)


Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

## Задание 4. Filebeat.
Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.
