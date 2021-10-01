[![Build status](https://ci.appveyor.com/api/projects/status/i6saa94o0a6s6d9a?svg=true)](https://ci.appveyor.com/project/Niksel00/ahj-diploma-frontend)

[Ссылка на GitHub Pages](https://niksel00.github.io/ahj-diploma-frontend/)<br>
[Репозиторий Backend](https://github.com/Niksel00/ahj-diploma-backend)<br>
[Ссылка на Heroku](https://ahj-workers-heroku.herokuapp.com/)<br>

---

Структура приложения (классы)
* Chaos.js – основной класс приложения. Отвечает за визуальный рендер.
* DOM.js – построение DOM-элементов.
* Request.js – логика общения с сервером через WebSockets.
* SidePanel.js – боковая панель Органайзера - Хранилище и категории.
* FileLoader.js – загрузка файлов, Drag & Drop.
* MediaLoader.js – запись, обработка видео и аудио сообщений.
* Geolocation.js – определение геолокации.
* Favourites.js – работа с избранными сообщениями.
* Pin.js – закрепление сообщения.