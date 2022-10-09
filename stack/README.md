# Стек технологий


+ __Frontend__
    + ReactJS
        + [GitHub](https://github.com/facebook/react)
        + [Документация](https://reactjs.org/docs/getting-started.html)
    

+ __Backend__ 
    + ExpressJS
        + [GitHub](https://github.com/expressjs/express)
        + [Документация](https://expressjs.com/ru/guide/routing.html)
        + ORM - [Sequelize](https://github.com/sequelize/sequelize)
    + Fiber
        + [GitHub](https://github.com/gofiber/fiber)
        + [Документация](https://docs.gofiber.io)
        + ORM - [GORM](https://github.com/go-gorm/gorm)
        

+ __Тестирование__ 
    + [Postman](https://github.com/postmanlabs)
    + [Siege](https://github.com/JoeDog/siege)
    

+ __Веб-вервер__
    + [nginx](https://ru.wikipedia.org/wiki/Nginx)
        + [GitHub](https://github.com/nginx/nginx)


+ __СУБД__
    + PostgreSQL
        + [GitHub](https://github.com/postgres/postgres)
        + [Документация](https://postgrespro.ru/docs/postgresql/14/index)
        
        
## FAQ

##### Что такое ORM? 
[Вики](https://ru.wikipedia.org/wiki/ORM)

##### На хабре пишут, что ORM - это анти-паттерн
С точки зрения ООП - может быть. Но кого это волнует, если Go - не объектно-ориентированный язык, а в JS до этого года не было инкапсуляции в принципе?

##### ORM замедляет сервер?
Да. Но облегчает работу с базой данных (пагинация, защита от SQL-инъекций и т.д.)

##### Почему именно эти технологии?
К выбору этих технологий пришли путём анализа требований проекта и желаний разработчиков.

##### А не прикроют лавочку?
Все технологии относятся к классу [свободного ПО](https://ru.wikipedia.org/wiki/Свободное_программное_обеспечение). С лиценциями можно ознакомиться в их GitHub репозиториях.

##### Почему не Apache WebServer?
Воля девопса.

##### Я разработчик. Обязательно ли мне читать документацию по nginx?
Нет.
