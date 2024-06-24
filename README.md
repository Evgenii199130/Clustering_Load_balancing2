# Clustering_Load_balancing2 Королев Е.В.

Задание 1

   Запустите два simple python сервера на своей виртуальной машине на разных портах
   Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
   Настройте балансировку Round-robin на 4 уровне.
   На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.

Ответ:
 ![1](https://github.com/Evgenii199130/Clustering_Load_balancing2/blob/main/scrin/1.1.jpg)
 ![1](https://github.com/Evgenii199130/Clustering_Load_balancing2/blob/main/scrin/1.2.jpg)
 ![1](https://github.com/Evgenii199130/Clustering_Load_balancing2/blob/main/scrin/1.3.jpg)
 ![1](https://github.com/Evgenii199130/Clustering_Load_balancing2/blob/main/scrin/1.4.jpg)


Задание 2

   Запустите три simple python сервера на своей виртуальной машине на разных портах
   Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
   HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
   На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.

Ответ:

 ![1](https://github.com/Evgenii199130/Clustering_Load_balancing2/blob/main/scrin/2.1.jpg)
 ![1](https://github.com/Evgenii199130/Clustering_Load_balancing2/blob/main/scrin/2.2.jpg)
 ![1](https://github.com/Evgenii199130/Clustering_Load_balancing2/blob/main/scrin/2.3.jpg)
 ![1](https://github.com/Evgenii199130/Clustering_Load_balancing2/blob/main/scrin/2.4.jpg)
