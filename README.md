
<i>Создать Deployment приложения, состоящего из Nginx.
Создать собственную веб-страницу и подключить её как ConfigMap к приложению.
Выпустить самоподписной сертификат SSL. Создать Secret для использования сертификата.
</i>
Создаем namespace nginx-ssl
Создаем Deploy

 

Генерируем самоподписанный сертификат и перекодируем полученные файлы в BASE64.

 


 

 

Создать Ingress и необходимый Service, подключить к нему SSL в вид. Продемонстировать доступ к приложению по HTTPS.
Предоставить манифесты, а также скриншоты или вывод необходимых команд.

Сервис и ингресс созданы.

 

Страница доступна по HTTPS.

 
