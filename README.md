
<i>Создать Deployment приложения, состоящего из Nginx.
Создать собственную веб-страницу и подключить её как ConfigMap к приложению.
Выпустить самоподписной сертификат SSL. Создать Secret для использования сертификата.
</i>

Создаем namespace nginx-ssl
Создаем Deploy

![alt text](https://github.com/powermetall/netology_02/blob/main/pic_1.png?raw=true) 

Генерируем самоподписанный сертификат и перекодируем полученные файлы в BASE64.

 ![alt text](https://github.com/powermetall/netology_02/blob/main/pic_2.png?raw=true)


 ![alt text](https://github.com/powermetall/netology_02/blob/main/pic_3.png?raw=true)

 ![alt text](https://github.com/powermetall/netology_02/blob/main/pic_4.png?raw=true)

<i>Создать Ingress и необходимый Service, подключить к нему SSL в вид. Продемонстировать доступ к приложению по HTTPS.
Предоставить манифесты, а также скриншоты или вывод необходимых команд.
</i>


Сервис и ингресс созданы.

 ![alt text](https://github.com/powermetall/netology_02/blob/main/pic_6.png?raw=true)

Страница доступна по HTTPS.

 ![alt text](https://github.com/powermetall/netology_02/blob/main/pic_6.png?raw=true)
