Одностранчное веб-приложение, получающее данные из openweathermap.org

Список команд, необходимый для локальной работы: 

```npm i -g npm - глобальная установка npm
npm i --save lodash - установка lodash для корректкной работы кода из init.js
npm i bootstrap - установка библиотеки bootstrap
npm i bootstrap jquery popper.js - установка jquery для корректной работы bootstrap
npm i --save-dev parcel-bundler @fortawesome/fontawesome-free - установка шрифтов, необходимых для bootstrap
npm i -g parcel-bundler - установка сборщика bundler parcel
```
Для сбора приложения и его последующего запуска выполните: 

```
parcel index.html
```
Теперь откройте http://localhost:1234/ в браузере.