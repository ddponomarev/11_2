# Домашнее задание к занятию "`ELK`" - `Пономарев Денис`

### Задание 1 Elasticsearch

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

*Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name*.

![Задание1](https://github.com/ddponomarev/10-3/blob/master/img/z1.png)

---

### Задание 2 Kibana

Установите и запустите Kibana.

*Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty*.


![Задание2](https://github.com/ddponomarev/10-3/blob/master/img/z2.png)

---

### Задание 3  Logstash

Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.*

![Задание3](https://github.com/ddponomarev/10-3/blob/master/img/z3.png)


---
### Задание 4 Filebeat.

Установите и запустите Filebeat. Переключите поставку логов Nginx с Logstash на Filebeat.

*Приведите скриншот интерфейса Kibana, на котором видны логи Nginx, которые были отправлены через Filebeat.*

![Задание4](https://github.com/ddponomarev/10-3/blob/master/img/z4.png)

---


### Задание 5 *. Доставка данных

Настройте поставку лога в Elasticsearch через Logstash и Filebeat любого другого сервиса , но не Nginx.
Для этого лог должен писаться на файловую систему, Logstash должен корректно его распарсить и разложить на поля.

*Приведите скриншот интерфейса Kibana, на котором будет виден этот лог и напишите лог какого приложения отправляется.*

![Задание5](https://github.com/ddponomarev/10-3/blob/master/img/z5.png)
