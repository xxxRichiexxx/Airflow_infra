Для запуска учебной инфраструктуры клонируйте к себе на ПК репозиторий:

    git clone https://github.com/xxxRichiexxx/Airflow_Infra

Далее выполните из папки "Airflow_Infra" следующую комманду:

    docker-compose up -d --build

После запуска данной комманды будет развернуто несколько контейнеров: 

* Airflow с базой метаданных Postgres;
* КХД на базе Postgres.

Подключитесь к контейнеру DWH с помощью Debeaver:

    login: de
    password: de

Зайдите в Airflow по следующей ссылке:

    http://localhost/home

Введите логин и пароль:

    login: airflow
    password: airflow