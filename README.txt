ИНСТРУКЦИЯ: ЗАПУСК REEF PLACE НА HEROKU

1. Установи Node.js и Heroku CLI:
   - https://nodejs.org/
   - https://devcenter.heroku.com/articles/heroku-cli

2. В терминале:
   cd ПАПКА_С_РАЗАРХИВИРОВАННЫМ_ПРОЕКТОМ
   npm install

3. Создай приложение:
   heroku login
   heroku create

4. Задеплой проект:
   git init
   git add .
   git commit -m "init"
   git push heroku master

5. Запусти:
   heroku open

6. В BotFather укажи ссылку на приложение:
   https://YOUR_HEROKU_APP.herokuapp.com

7. Готово!
