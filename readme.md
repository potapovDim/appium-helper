Хелпер по встановленню та налаштуванню [appium](https://github.com/appium/appium)

Для роботи з appium необхідно встановити [nodejs](https://nodejs.org/)


iOS 
Для початку автоматизацї мобільних додатків необхіно 
1. Встановити [Xcode](https://developer.apple.com/xcode/)
2. Встановити [appium](https://github.com/appium/appium)
* Встановлення appium в глобал файлової системи ```npm i -g appium```. При встановленні appium в глабал файлової системи його можна виклика з будь-якого місця написавши в терміналі ```appium```. 
Якщо ви використовуєте [nvm](https://github.com/creationix/nvm) nodejs менеджер версій, ваші глабальні пакети ```nodejs``` будуть знаходитися ```/.nvm/versions/node/актуальна версія nodejs/lib/node_modules```, для знаходження виконуваного файла nodejs в терміналі виконайте команду ```where node``` після чого буде відображений шлях до виконуваного файлу і до директорії ```nodejs```
* Встановлення appium в локальний проект ```npm i --SD appium```, або ```npm i --S appium```. В цьому випадку доступ до appium можна отримати через ```${projectDir}/node_modules/.bin/appium```, чи в розділі ```scripts``` package.json файлу, приклад нижче
```json
...
"scripts": {
  "start-appium": "appium"
}
...
```
 ```npm run start-appium``` запустить appium 