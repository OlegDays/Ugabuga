# Ugabuga
кряк звёздочки


Туториал по кряку star uml (сработало для 7.1.0)
1.	Качаем отсюда node.js : https://nodejs.org/en/download
2.	Качаем star uml с официального сайта
3.	Открываем cmd от имени администратора
4.	Переходим в директорию StarUM\resources  : cd "C:\Program Files\StarUML\resources"
5.	Проверяем : пишем node - v и npm -v (если ничего не вывелось то плохо, переустанавливаем  1 пункт. Должны выйти версии)
6.	Пишем в cmd:  npm install -g asar
7.	Пишем в cmd:  asar extract app.asar app
8.	Переходим в проводнике в C:\Program Files\StarUML\resources\app
9.	Меняем app/src/engine/license-store.js
10.	Меняем app/src/engine/diagram-export.js
11.	Меняем app/src/dialogs/license-activation-dialog.js

Файлы есть в директории
12.	Пишем в cmd: asar pack app app.asar
13.	Пишем в cmd: cmd /c rmdir /s /q app

Поздравляю, staruml крякнут.
