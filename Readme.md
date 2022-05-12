### EN
This manual for those people who want to start learning WEB technology (php, html, css) in 2022, but does't know how to install WEB server

1. Install docker [from official site](https://docs.docker.com/desktop/windows/install/)
2. Enter: <code>
   docker run -v /Users/devops/devops/docker/php:/var/www/html -p 80:80 php:apache </code>  See [/screens/2.png](screens/2.png)

3. Enter in browser [http://127.0.0.1](http://127.0.0.1) (will executing index.php)

4. Enter in browser [http://127.0.0.1/getAuthor.php](http://127.0.0.1/getAuthor.php) or [http://127.0.0.1](http://127.0.0.1). See [/screens/3.png](screens/3.png)
   Look at files getAuthor.php and index.php . Try to change something
5. Create index.html and try to write some html code

### RU
Руководство для тех людей кто хотел бы изучить PHP и HTML в 2022, но не знает как установить web сервер и заставить ваш код работать

1. Установить docker [c официального сайта](https://docs.docker.com/desktop/windows/install/)
2. Выполнить: <code>
   docker run -v /Users/devops/devops/docker/php:/var/www/html -p 80:80 php:apache </code>  Смотри [/screens/2.png](screens/2.png)

3. Ввести в браузере [http://127.0.0.1](http://127.0.0.1) (выполниться index.php)

4. Ввести в браузере [http://127.0.0.1/getAuthor.php](http://127.0.0.1/getAuthor.php) и [http://127.0.0.1](http://127.0.0.1). Смотри [/screens/3.png](screens/3.png)
   Посмотреть соответствующие getAuthor.php и index.php - попробовать поменять что-либо
5. Создать index.html файл и скопировать или написать какой-то код
