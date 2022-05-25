# Обрезка ссылок с помощью Битли
Данный скрипт создан, что бы можно было обрезать длинные ссылки и сделать их короткими с помощью сервиса bitly.com
Так же можно будет после создания ссылки посмотреть, сколько раз по ней делался переход на Ваш сайт за всё время.

## Как установить:
Перед взаимодействием в API Bitly нужно получить токен.
Токен выглядит как строка наподобие следующей: `17c09e20ad155405123ac1977542fecf00231da7`

Как получить токен описано по [этой ссылке](https://dev.bitly.com/get_started.html)

После получения токена создаем файл `".env"` в коренной папке скрипта и вставляем ваш токен: ``BITTLY_TOKEN = ВАШ ТОКЕН ``

Сохраняем файл.

Python3 должен быть уже установлен. 
Затем используйте `pip` (или `pip3`, есть конфликт с Python2) для установки зависимостей:
```
pip install -r requirements.txt
```

### Цель проекта

Код написан в образовательных целях на онлайн-курсе для веб-разработчиков [dvmn.org](https://dvmn.org/).
