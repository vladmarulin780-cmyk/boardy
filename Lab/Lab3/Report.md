![проверка работы nginx'а](screenshots/01-nginx-status.png)
![страничка nginx](screenshots/02-browser-ip.png)
![строку запроса, код ответа и Content-Type подписал на скрине](screenshots/03-curl.png)
![это ПОСЛЕ смены владельца](screenshots/04-permissions(after.png)
![это ДО смены владельца](screenshots/04-permissions(before.png)
5 задание
listen - на каком порту слушааем
root - корень сервера, по которому ходит nginx по умолчанию
server_name - непосредственно имя сервера
insex - он помогает nginx'у найти файл(например, главной странички), в том случае, когда в пути не указан конкретный файл, то есть nginx по умолчанию возьмет файлик, который там указан и отдаст пользвателю
![dns зона bulochka(тут на само деле очень смешно получилось, мой друг первее меня добавил себе зону ai-info, поэтому beget не давал мне создать такой домен)](screenshots/05-dns-zone.png)
![А-запись(а тут не получилось изменить ttl, ругается, писал в поддержку, говорят, мол, нужно решать этот вопрос на стороне netangels)](screenshots/06-a-record.png)
![пропинговал](screenshots/07-ping.png)
![вывод dig'а, подписал все на скрине](screenshots/08-dig.png)
![тут вывод dig +trace, 4 шага выделил так же на скриншоте(не до конца понял на самом деле, почему у просто dig'a ttl = 102, а у gig +trace ttl = 600, может я не то нашел?)](screenshots/09-dig-trace.png)
![страничка nginx, но уже по домену bulochka.ai-infi.ru](screenshots/10-browser-domain.png)
