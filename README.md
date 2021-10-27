# test-ITKEY
Test project for ITKEY

## Задача:

Есть сайт: https://skai.sk.ru/en/sustaintech_map/
На сайте есть блок:
![image](https://user-images.githubusercontent.com/27223135/139025849-b41fef79-4a54-4437-a861-35378e39aced.png)

Его нужно воспроизвести на базе React (кроме логотипов компании).
Исходные данные: Шрифты, SVG иконки, JSON ответов сервера - все находится в
архиве в приложении.

### Требования:
В результате должен получиться проект на базе npm пакетов, который можно запустить
на локальном компьютере. Запросы к серверу (JSON файлам) нужно эмулировать на
простейшем уровне, без каких-то особенных заморочек (Отдельный сервер для JSON
файлов поднимать не нужно, но и простейшие изменения настроек должны позволять
сделать запросы к реальному серверу с данными). Все растровые картинки заменить
на блоки с SVG кодом, CSS параметры брать из исходного сайта. Важно сохранить
адаптивность данного блока.
Желательно: Использовать sass, scss или style для написания стилей вместо CSS
Дополнительное задание: Будет плюсом реализация данного блока в качестве
виджета. Т.е. возможность после запуска проекта на локальном компьютере, кроме
возможности просто отобразить его в браузере, иметь возможность встроить его
простым тегом <script> (или парой тегов) в любой локальный html файл с сохраненной
страницей другого сайта. Соответственно открыв этот локальный html файл в браузере
мы должны увидеть кроме содержания самого файла еще и рабочий виджет. Виджет
при этом должен адаптировать свои размеры и стили под занимаемое им свободное
место.
  
### P.S. Точное воспроизведение скролл баров не требуется, достаточно чтобы это не
были стандартные полосы прокрутки браузера.
  
###P.P.S. Достаточно воспроизвести этот виджет на одном языке. Но можно добавить
поддержку 2х языков рус/англ в json все данные для этого присутствуют.
Переключение языка через интерфейс не требуется
