# Задача:

* Ставим случайный User-Agent из файла.
* Открываем браузер (chromium) и заходим на google.com.
* Отключаем javascript
* Вводим поисковые запросы из файла (по очереди).
* Ищем на странице с результатами рекламу.
* Сверяем домен на который ведёт рекламная ссылка с доменом который указан в конфиге .
* Если домен совпал открываем сайт, находимся на нём n времени (задаётся в конфиге), иначе закрываем браузер и двигаемся дальше.
* Закрываем браузер.
* Открыть некоторое приложение "Alpha", подождать n времени (задаётся в конфиге).
* Закрыть приложение "Alpha"
* Повторить действия описанные выше для всех поисковых запросов.
