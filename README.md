js скрипт, адаптирующий верстку страниц сайта rsdn.ru для удобного просмотра на мобильных устройствах. Скрипт срабатывает после загрузки страницы и модифицирует ее — накладывает стили, удаляет лишние элементы, меняет верстку.
Для использования нужно в настройках профиля добавить ссылку на скрипт https://rawgit.com/SergeyA/rsdn-mobile-view/master/rsdn-mobile-view.js.

Для переключения на мобильный вид нужно нажать на кнопку на главной странице сайта (см. скриншот ниже). 
Если отказаться от переключения, то сайт будет функционировать в обычном режиме.

Из за того, что github отдает файлы без указания ContentType, скрипт нужно загружать через сервис rawgit.com или аналогичный. 

Ссылка с правильным ContentType: https://rawgit.com/SergeyA/rsdn-mobile-view/master/rsdn-mobile-view.js

Минус такого способа в том, что rawgit кэширует файл и обновляет его не мгновенно, а только раз в несколько минут.

Скрипт подключает гугланалитику для отслеживания скорости загрузки страниц. А знание количества активных пользователей будет стимулировать меня на дальнейшее развитие скрипта (или наоборот ))). 

Скриншоты:

Главная страница с кнопками переключения на мобильный вид

![Главная страница](https://raw.githubusercontent.com/SergeyA/rsdn-mobile-view/master/doc/img/screenshot_home.png)


Список форумов

![Список форумов](https://raw.githubusercontent.com/SergeyA/rsdn-mobile-view/master/doc/img/screenshot_forums.png)


Список тем

![Список тем](https://raw.githubusercontent.com/SergeyA/rsdn-mobile-view/master/doc/img/screenshot_topics.png)


Список сообщений

![Список сообщений](https://raw.githubusercontent.com/SergeyA/rsdn-mobile-view/master/doc/img/screenshot_posts.png)

