                            Отчет по Практической работе №1

Задание 2
![IP-адрес:192.168.106.129](screenshots/04-ip-addr.png)
![ssh слушает на 53 порту](screenshots/05-ports.png)
свободные порты есть

Задание 3
![ssh сервис в активном состоянии, PID - 2218, слушает на 22 порту, автозапуск включен](screenshots/06-ssh-status.png)

Задание 4
![35 пользователей, трое с bash](screenshots/08-users.png)
![в 2 группах: boardy, sudo](screenshots/10-user-check.png)

Задание 5
основные каталоги: bin, boot, dev, etc, home, root, tmp, usr, var
etc - конфиги
var - веб, логи
home - папка пользователя
tmp - временные файлы
![скрытые файлы: bash_history, bash_logout, bashrc, cache/, lesshst, profile, ssh](screenshots/12-home-tree.png)

Задание 6
На /etc/shadow права 640(-rw-r-----), для того чтобы хэши паролей не были доступны всем пользователям
При chmod 755: владелец может читать, писать, выполнять. Остальные - читать, выполнять
При chmod 600: доступ только для владельца(читать, писать)

Задание 7
Всего пакетов - 619
![ключевые пакеты:](screenshots/15-packages.png)
![запущенные сервисы:](screenshots/16-services.png)