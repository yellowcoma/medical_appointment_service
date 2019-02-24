# Установка:
1) Создать пустую базу данных
2) Импортировать в созданную базу таблицу с помощью файла med_app.php
3) Скопировать все файлы проекта кроме med_app.php в корневую директорию сайта

# Описание структура директорий и файлов:
+ med_app.sql                           - Здесь описана таблица базы данных используемая приложением.
+ index.php                             - Оболочка приложения, запускается первым, все действия происходят через него
+ /core/                                - Классы необходимые для работы приложения
+ /core/Сrud.php                        - Класс содержит функции CRUD + функцию валидации даты согласно требованиям задачи
+ /core/Base.php                        - Класс содержит свойства и методы для подключения базы данных
+ /vendors/                             - Для подключения сторонних файлов и библиотек
+ /vendors/foundation-6.5.1-custom/     - Файлы фреймворка foundation, отвечает за визуальное оформление, подключается в header.php и footer.php
+ /views/                               - Файлы шаблонов
+ /views/form.php                       - Файл для вывода формы для создания и редактирования заявки
+ /views/list.php                       - Файл для вывода списка имеющихся записей
+ /views/parts                          - Шаблоны служебных частей страницы, подключаются в основных шаблонах form.php и list.php
+ /views/parts/header.php               - Файл отвечающий за вывод верхней части кода
+ /views/parts/footer.php               - Файл отвечающий за вывод нижней части кода



