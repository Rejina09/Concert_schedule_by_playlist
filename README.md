# Yandex Music Concert Schedule Bot

Этот бот для Telegram принимает ссылку на плейлист Яндекс Музыки и возвращает список концертов исполнителей из плейлиста. 

## Содержание
- [Технологии](#технологии)
- [Структура проекта](#структура-проекта)
- [Сборка](#сборка)
- [Для пользователей](#для-пользователей)
- [Тестирование](#тестирование)
- [To do](#to-do)
- [Команда проекта](#команда-проекта)

## Технологии
- []
  //дописать или удалить раздел
  
## Структура проекта

### [playlist.py](https://github.com/Rejina09/Concert_schedule_by_playlist/blob/main/playlist.py)
Файл содержит ...
//дописать (Марго)

### [test_playlist.py](https://github.com/Rejina09/Concert_schedule_by_playlist/blob/main/test_playlist.py)
Файл содержит тесты, проверяющие работу функций, которые проверяют корректность ссылки от пользователя.
//дописать (Марго)

### [concert_searcher.py](https://github.com/Rejina09/Concert_schedule_by_playlist/blob/main/concert_searcher.py)
//дописать (Илья)

### [test_concert_searcher.py](https://github.com/Rejina09/Concert_schedule_by_playlist/blob/main/test_concert_searcher.py)
Файл содержит тесты ..
//дописать (Илья)

### [bot.py](https://github.com/Rejina09/Concert_schedule_by_playlist/blob/main/bot.py)
//дописать (Регина)


## Сборка
Как установить, запустить от лица разработчика.

### Требования
Необходимо наличие некоторых библиотек и пакетов, которые можно установить с помощью ```pip install <package_name>``` .

### Работа с токеном
Вам необходимо создать файл config.py, в котором будет токен на вашего бота и токен на аккаунт пользователя Яндекс.Музыки. Выглядеть он должен так:
```
TELEGRAM_API_TOKEN = "token_your_bot"

YANDEX_MUSIC_TOKEN = "token_your_account"
```
Где взять токен для бота? -
При создании бота он выдаётся автоматически.

Где взять токен на Яндекс.Музыку? -
Скачать одно из расширений в засисимости от используемого браузера.

[Для Google Chrome](https://chromewebstore.google.com/detail/yandex-music-token/lcbjeookjibfhjjopieifgjnhlegmkib?pli=1)

[Для Firefox](https://addons.mozilla.org/en-US/firefox/addon/yandex-music-token/)

Авторизорваться по одной из ссылок выше, скопировать полученный при регистрации токен.
//проверить на достоверность (Марго)

### Запуск проекта
Запускаете файл bot.py и можете пользоваться ботом.

## Для пользователей
Необходимо начать работу с ботом с помощью команды ```\start```, передать ему ссылку на свой плейлист Яндекс.Музыки. Более подробный процесс работы с ботом можно увидеть [здесь](https://drive.google.com/file/d/1BE8hUgLY5ckMS5GE33efrkJi7DDHaWyx/view?usp=drive_link).

## Тестирование
В файле [test_playlist.py](#test_playlist.py) содержатся тесты для [playlist.py](#playlist.py) .проверки обработки ссылки на плейлист и самого плейста.
В файле [test_concert_searcher.py](#test_concert_searcher.py) содержатся тесты для [concert_searcher.py](#concert_searcher.py).

На гугл-диске содержатся [видеоотчет](https://drive.google.com/file/d/1BE8hUgLY5ckMS5GE33efrkJi7DDHaWyx/view?usp=drive_link) по тестированию работы нашего бота, [файл](https://docs.google.com/document/d/1A92xYJe9rlYYSt_doerm0t5KUxjPn9rurxx16zNw1BE/edit?tab=t.0) с фото-отчетом по тестированию работы бота, [видеоотчет](https://drive.google.com/file/d/10lFCnpHITtT_FWFlqPJqIvQNW_8BnVeA/view?usp=drive_link) тестирования кода Телеграм бота.

## To do
- [x] Телеграм бот. 
- [x] Функция, обрабатывающая ссылки на корректность.
- [x] Функция, получающая ссылку на плейлист и возвращающая список из первых 5 исполнителей.
- [x] Класс, ищущий концерты по имени исполнителя.
- [x] Написать README
- [ ] Добавить кнопки в Телеграмм бот для дополнительных опций (дата концерта, город, и т. д.).
- [ ] Написать логику для того, чтобы ставить ограничения на даты концертов и их города и т. д.
- [ ] Добавить логику для выбора конкретных исполнителей, критерия, по которому их бот будет отбирать.
- [ ] ...
- [ ] Получить 10:)

## Команда проекта
![image](https://github.com/user-attachments/assets/b4b66617-0376-458c-a155-61769e2488c6)

- [Илья Шеин](https://t.me/ilya_shn) — парсинг концертов по названию исполнителей, настройка сервера с итоговым ботом.
- [Маргарита Самородова](https://t.me/sam_vader) — анализ плейлиста по ссылке с Яндекс Музыки.
- [Регина Сабирьянова](https://t.me/rejinasab) — работа в создании тг-бота (в основном логика работы с пользователем).
- [Мария Дёминова](https://t.me/mariaskai13) — работа в создании тг-бота (в основном создание кнопок для пользователя).

## Источники
//дописать 
