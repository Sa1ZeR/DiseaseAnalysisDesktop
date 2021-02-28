### Disease Analysis for Desktop

---
### Ни в коем случае не приступайте к работе с репозиторием, пока не прочитаете весь инструктаж

##### Инструктаж

Работа над этим проектом разделена по веткам:

1.back-end

2.front-end

3.bd


Каждая команда работает в основной ветке. Любой человек в команде может отправить pull request на 
добавление изменений в основную ветку проекта. Если всё правильно, то владелец репозитория
одобряет изменения в проект.

---

## Front-end
Команда front-end работает с папкой DiseaseAnalysisDesktop/src/main/resources/views/.
Задача фронта разработать .fxml файлы с для реализации пользовательского интерфейса.
.fxml файлы будут отвечать за различные сцены в приложении.


Просьба называть .fxml файлы однозначно.


Также команда front-end должна скидывать код контроллера из опции View->Show Sample Controller
Skeleton для удобства разработки back-end.


НЕ ЗАБУДЬТЕ ОТРЕДАКТИРОВАТЬ В .fxml путь к контроллерам(Например: x:controller="controllers.UsersController")


Обязательно установите SceneBuilder именно под java 8.
Импортируйте в Scene Builder библиотеку JFoenix.

Здесь вся необходимая информация о JFoenix:
[JFoenix](https://github.com/sshahine/JFoenix)


Советую активно пользоваться css параметрами для большей настройки красоты интерфейса :)

---

## Back-end
Команда back-end работает с папкой DiseaseAnalysisDesktop/src/main/java/


Задачи:

*Разработать под соответствующий план графического интерфейса контроллеры

*Разработать DAO классы для работы базы данных через модели

*Разработать соответсвующие модели, которые необходимы для построения логики
системы




---

## BD
Команда bd работает с папкой DiseaseAnalysisDesktop/src/main/java/db/

Задачи:

*Импортировать данные из excel таблицы в базу данных

*Разработать структуру базу данных

*Написать необходимые запросы под логику программы


---



## В репозитории представлен небольшой пример работы проекта. 

# Перед этим измените поле PATH в классе UserDAO(DiseaseAnalysisDesktop/src/main/java/dao/), которое отвечает за путь к бд, на соответствующий абсолютный путь у себя  


Main класс для запуска примера находится по пути DiseaseAnalysisDesktop/src/main/java/.


Здесь обычная выгрузка данных из бд по нажатию кнопки. Вся логига запросов к бд находится в классе UserDAO.
В качестве модели я взял обычного User. В UsersController вся работа с графическими элементами и событиями.
Вы также можете в режиме реального времени добавить ещё данные в бд и при повторном нажатии на кнопку 
новые данные выгрузятся на экран. 


