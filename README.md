# StarWars - API request
*Каталог эпизодов Star Wars с выводом детальной информации о каждом фильме*
[Посетить страницу](http://star-wars.webtm.ru/)


![](https://img.shields.io/badge/version-1.0.0-green)

___



**Учебная работа в рамках профессии от SkillBox "Fullstack-разработчик"** (курс - JavaScript «Продвинутый уровень»).

**Основные характеристики:**

+ Приложение имеет два вида страниц:
    +  Главная страница. На ней загружается и отображается список эпизодов с указанием номера и названия в каждом элементе. Элементы являются ссылками на детальную страницу эпизода.
    +  Детальная страница эпизода загружает и показывает информацию об эпизоде.
+ Код для соответствующей страницы загружается с помощью динамического import'а, то есть только если он нужен на текущей странице. В проекте разделены код отрисовки DOM-дерева и код получения данных из API.
+ Стили также загружаются асинхронно. Страница не отображается до тех пор, пока все необходимые ресурсы для нее не загрузились (используется preloader).
+ Переходы по ссылкам не приводят к перезагрузке страницы.

![](https://imageup.ru/img179/4053227/starwars.jpg)
![](https://imageup.ru/img147/4053228/starwars-details.jpg)

