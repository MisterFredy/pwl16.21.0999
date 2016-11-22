@ECHO OFF
start c:/nginx/nginx.exe
Echo WebServer hasbeen started
cd c:/nginx/php
php-cgi -b 127.0.0.1:9000
exit