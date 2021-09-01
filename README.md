# REACT-JazzTeam-FrontendDeveloper-TestTask
Test task on a position Frontend Developer

## Описание задачи: 
Реализовать приложение, которое будет отображать несколько страниц, в зависимости от url браузера. Серверную часть программировать не нужно. Оформление и дизайн на ваше усмотрение, проявите творчество, сделайте так, чтобы можно было комфортно смотреть на приложение в браузере.
    
## Необходимо решить задание, используя следующий стек технологий:
- JavaScript
- Web-фреймворк на выбор:
- React/Redux
- Angular/NgRx
- CSS - не использовать сторонних CSS-библиотек или препроцессоров

## Описание страниц:
<img src="/map.jpg" height="500px">

| NAME | ENCRYPT | DESKRIPTION |
|----------------|:---------:|:----------------:|
| /              | Главная страница|  |
| /login         |       Авторизация |   Cтраница авторизации  |
| /profile       | Профиль | Cтраница, которая отображает любую информацию об авторизованном пользователе. Должна быть закрыта без авторизации |
| /info          |     Информация | Cтраница с любой однородной информацией|

- / (Главная страница).
- /login - Авторизация ()
- /profile - Профиль (Cтраница, которая отображает любую информацию об авторизованном пользователе. Должна быть закрыта без авторизации)
- /info - Информация (Cтраница с любой однородной информацией)

- [ ] реализовать боковую или верхнюю панель навигации, которая будет отображаться на всех страницах приложения и содержать ссылки на главную страницу, на страницу с информацией (/info) и на страницу пользователя (/profile).

- [ ] реализовать переход на страницу Авторизация при попытке войти в Профиль, если пользователь не авторизован.

- [ ] реализовать отображение имени авторизованного пользователя на панели навигации.

- [ ] для авторизации пользователя использовать фейковые данные username: Admin, password: 12345678.

- [ ] при вводе правильных данных необходимо реализовать переход на страницу профиля пользователя.

- [ ] при попытке ввести некорректные данные отображать сообщение "Имя пользователя или пароль введены неверно".


## Календарь

Реализовать страницу календаря (/calendar) в соответствии с макетом:

- [ ] страница должна быть закрыта без авторизации.

- [ ] реализовать Добавление/Редактирование событий пользователя в календарь.

- [ ] реализовать переход по месяцам.

- [ ] реализовать поиск событий в календаре.

- [ ] на странице Профиль отобразить созданные события пользователя.

## Таблица с данными

Реализовать в приложении страницу, на которой будет отображена таблица с данными. Путь url, по которому страница будет доступна в приложении, на ваше усмотрение.

- страница должна быть закрыта без авторизации.

- исходные данные для таблицы реализовать в json формате и поместить в отдельный json файл. Какие именно данные на ваше усмотрение, проявите фантазию.

- количество колонок и строк должно быть таким, чтобы в таблице отображались горизонтальная и вертикальная полосы прокрутки.

- заголовки колонок таблицы должны быть зафиксированными, чтобы при вертикальном скролле они всегда отображалась на экране.

- первая колонка должна быть зафиксирована, чтобы при горизонтальном скролле она всегда отображалась на экране.

- реализовать выделение строк таблицы. Выделите любым цветом, на ваше усмотрение рамки, строки.

- реализовать панель состояния вверху или внизу таблицы, на которой должно быть отображено общее количество данных и количество выделенных строк в таблице.

- реализовать редактирование ячеек таблицы.

## Дополнительные условия
Код приложения поместить в GitHub репозиторий с описанием. 
Каждую отдельную задачу тестового задания оформить отдельным коммитом.
