# todo-app

Разработать приложение “Менеджер задач”.  

Функционал: 

- Добавление задачи 

- Удаление задачи 

- Возможность отметить задачу выполненной/активной 

- Три фильтра по задачам All (все), Active (активные), Completed (выполненные) 

- Счетчик всех задач 

Задачи и их статусы сохраняются в БД LiteSQL через операции с моделями Django 

При перезагрузке страницы отображаются задачи из БД с  

Добавление, удаление, отметка задачи производится через Ajax запросы на JavaScript 

 

Проект с изображениями для верстки: https://github.com/vladefr97/polytech-todo-task







```shell
python manage.py migrate

python .\manage.py sqlmigrate todo 0001

python .\manage.py makemigrations      

python .\manage.py runserver

```