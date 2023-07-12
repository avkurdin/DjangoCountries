# django-countries

## Как запускать
#### 1. Создать виртуальное окружение
```commandline
python -m venv venv
```
#### 2. Активировать виртуальное окружение
##### Unix
```commandline
source /venv/bin/activate
```
##### Windows
```commandline
.\venv\scripts\activate.ps1
```

#### 3. Установить зависимости
```commandline
pip install -r requirements.txt
```

#### 4. Запустить сервер
```commandline
python /djangoCountries/manage.py runserver
```

## Задания
* [x] Создайте новый проект DjangoCountries. Создайте новое виртуальное окружение(venv), установите в него Django. 
* [x] Главная страница должна быть доступна по корневому url’у. На ней разместите произвольное приветствие c минимальным HTML оформлением. 
* [x] Запустите проект и проверьте отображение главной страницы. 
* [x] Загрузите ваш проект на GitHub 
* [x] Оформите главную страницу в виде полноценного html-документа 
* [x] Список с данными для стран возьмите тут. 
* [x] По url: /countries-list/ отобразите нумерованный список всех стран, отобразив в списке только названия стран. 
* [x] Название каждой страны сделайте гиперссылкой, которая ведет на персональную страницу данной страны. На персональной странице страны отобразите ее название(в виде заголовка) и список всех языков, на которых говорят в данной стране. 
* [x] На главной странице добавьте еще одну ссылку “Языки”. По ссылке отобразите страницу со списком всех языков на котором говорят во всех странах.
* [x] Создайте модель-класс Country. 
* [x] Перенесите все страны из исходного json файла в базу данных(БД). 
* [x] Измените работу вашего приложения на работу с БД 
* [x] Выгрузите данные из БД в фикстуру(fixture) countries.json 
* [x] Используя информацию с занятия, измените структуру БД, реализовав связь “многие-ко-многом” для стран и языков. 
* [x] Добавьте в проект файл requirements.txt 
* [x] Добавьте в проект файл README.md, добавив в него:
  * Информацию о запуске проекта после клонирования 
  * Список всех заданий, пометив выполненные 
* [x] На главной странице добавьте еще одну ссылку “Языки”. По ссылке отобразите страницу со списком всех языков на котором говорят во всех странах. 
* [x] Все языки в списке сделайте гиперссылками, каждая ведет на отдельную страницу, на которой отображаются страны, которые говорят на выбранном языке. 
* [x] Наверху страницы со списком стран добавьте алфавит, каждая буква которого является гиперссылкой. Каждая гиперссылка(на букве) ведет на страницу на которой отображаются только страны на выбранную букву. См. аналогию тут. 
* [x] Внизу страницы со списком стран реализуйте пагинацию. На каждой странице отобразите 10 стран.