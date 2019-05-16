## О том как запустить

Настройка окружения

1)Вам нужно копировать и использовать этот код: <strong>git clone https://github.com/AlekseiDeveloper/web-project.git</strong> или скачать архив.

2)После после используем эту команду: <b>php composer.phar install</b>

3)Необходимо зайти в корень проекта и создать
 <strong> .env </strong> file с такими настройками как указано в env.exemple и настроить его для связи с базой данных которую вы хотите использовать (настройки должны содержать подключение к вашей базе данных использующую sql). база должна быть создана в кодировке utf8_geniral_ci .
 
4)Создаем миграции: <b> php artisan migrate </b> 

5)Заполняем Таблицы: <b> php artisan db:seed </b>

6)Используем эту команду для создания сервера: <b>php artisan serve</b>
и переходим сюда http://127.0.0.1:8000

7)Заходим на сайт что бы зайти с правами admin вам понадобится, login: <b> admin@mail.ru </b> , password: <b> 123123123 </b>.
 или можете зарегистрировать нового пользователя и попасть в личный кабинет.
 

