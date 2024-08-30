# **Домашнее задание к занятию «Кластеризация и балансировка нагрузки» SYS-32 - Кумышев Аслан**

# * Задание 1 *
Что нужно сделать:

* Запустите два simple python сервера на своей виртуальной машине на разных портах
* Установите и настройте HAProxy, воспользуйтесь материалами к лекции по [ссылке](https://github.com/netology-code/sflt-homeworks/tree/main/2)
* Настройте балансировку Round-robin на 4 уровне.
* На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

  [🛠️Файл haproxy](https://github.com/sAslank/Balans/blob/main/file/dz1haproxy.cfg.txt)



1. ![alt text](https://github.com/sAslank/Balans/blob/main/img/1х1.jpg)
2. ![alt text](https://github.com/sAslank/Balans/blob/main/img/1х2.jpg)
3. ![alt text](https://github.com/sAslank/Balans/blob/main/img/1x4.jpg)

 **************************************************************************

# * Задание 2 *
Что нужно сделать:
* Запустите три simple python сервера на своей виртуальной машине на разных портах
* Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
* HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
* На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.

[🛠️Файл haproxy](https://github.com/sAslank/Balans/blob/main/file/dz2haproxy.cfg.txt)

1. ![alt text](https://github.com/sAslank/Balans/blob/main/img/2x2.jpg)
