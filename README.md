# movies-list
Приложение для  для хранения информации о фильмах:
- Использован MVC-паттерн
- Отношения в БД : фильм-актеры(многие-ко-многим), фильмы-формат(много-к-одному)
- ПДО-класс DB и фронт-контроллер обернуты в синглтоны
- Роутинг осуществляется фронт-контроллером
- Рендеринг представлений осуществляется методом render модели Renderer
- На момент написания этого ридми, парсинг файла с последующей записью в БД не доделан и выглядит ужасно
- Так же, на момент написания ридми, модели "кривоваты" нуждются в рефакторинге
- Модель для записи данных о фильме строится фабричным методом
