# Домашнее задание
Сценарии iptables
1) Реализовать knocking port, centralRouter может попасть на ssh inetrRouter через knock скрипт. Пример в материалах.
2) добавить inetRouter2, который виден(маршрутизируется) с хоста
3) Запустить nginx на centralServer.
4) Пробросить 80й порт на inetRouter2 8080.
5) Дефолт в инет оставить через inetRouter.


Параметры для запуска скрипта и вывод:

knock.sh 192.168.255.1 8881 7777 9991

Starting Nmap 6.40 ( http://nmap.org ) at 2019-11-06 19:29 UTC
Warning: 192.168.255.1 giving up on port because retransmission cap hit (0).
Nmap scan report for 192.168.255.1
Host is up (0.00031s latency).
PORT     STATE    SERVICE
8881/tcp filtered unknown
MAC Address: 08:00:27:3F:8C:12 (Cadmus Computer Systems)

Nmap done: 1 IP address (1 host up) scanned in 0.19 seconds

Starting Nmap 6.40 ( http://nmap.org ) at 2019-11-06 19:29 UTC
Warning: 192.168.255.1 giving up on port because retransmission cap hit (0).
Nmap scan report for 192.168.255.1
Host is up (0.00032s latency).
PORT     STATE    SERVICE
7777/tcp filtered cbt
MAC Address: 08:00:27:3F:8C:12 (Cadmus Computer Systems)

Nmap done: 1 IP address (1 host up) scanned in 0.15 seconds

Starting Nmap 6.40 ( http://nmap.org ) at 2019-11-06 19:29 UTC
Warning: 192.168.255.1 giving up on port because retransmission cap hit (0).
Nmap scan report for 192.168.255.1
Host is up (0.00034s latency).
PORT     STATE    SERVICE
9991/tcp filtered issa
MAC Address: 08:00:27:3F:8C:12 (Cadmus Computer Systems)

Nmap done: 1 IP address (1 host up) scanned in 0.15 seconds
