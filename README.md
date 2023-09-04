![example workflow](https://github.com/lekseff/Bot_Frontend/actions/workflows/deploy.yml/badge.svg)

[GitHub Pages](https://lekseff.github.io/Bot_Frontend/)

## Дипломная работа по курсу "Продвинутый JavaScript"

Здесь представлен бот, который предназначен как для хранения информации в виде текстовых сообщений, изображений, аудио и видео файлов. Также бот имеет интеграцию с несколькими сервисами API. Он может получать погоду используя Ваше местоположение, новости, курсы таких валют как доллар(USD), евро(EUR), Bitcoin(BTC).

- Подключение к серверу происходит автоматически. При успешном подключении показывается зеленый индикатор и кнопка 'Connect' не активна. Если произойдет отключение цвет индикатора изменится на красный и кнопка станет активной. Можно пробовать подключиться нажатием на кнопку. (Возможно Вам повезет)
- При подключении нескольких ботов сообщения будут видны всем участникам. Сообщения команд, геолокация и ответы на эти команды видны только отправившему их участнику. Также они не сохраняются в истории.
- Бот сохраняет сообщения на сервере. Если в тексе имеются ссылки они дополнительно выделяются. Отправка сообщения возможна по клавише 'Enter' или при клике на иконку отправить. При подключении к серверу происходит загрузка последних 10 сообщений из истории. ![](./pic/screen/1.jpg)
- По мере просмотра ленты сообщений они автоматически подгружаются с сервера.
- Для загрузки доступны файлы изображений, аудио и видео. Загрузить файлы можно по кнопке загрузить(скрепка) или перетащив файл в область сообщений. 
 ![](./pic/screen/2.jpg) Загрузка через DnD: ![](./pic/screen/3.jpg) Изображения: ![](./pic/screen/img.jpg) Аудио файлы: ![](./pic/screen/4.jpg) Видео файлы: ![](./pic/screen/vid.jpg) Если загрузка файла не поддерживается появится сообщение об ошибке: ![](./pic/screen/err.jpg)
 - Чтобы скачать файл необходимо выбрать сохранить.Если это изображение то достаточно кликнуть по нему и откроется окно выбора места сохранения.
  ![](./pic/screen/dowload.jpg)

## Геолокация
