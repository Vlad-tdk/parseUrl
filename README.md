# ParseUrl

# Инструмент извлечения ссылок с помощью Python

Этот инструмент представляет собой скрипт на Python для извлечения внутренних и внешних ссылок с веб-сайтов. Он позволяет обходить указанные в файле сайты, извлекать ссылки и сохранять их в текстовые файлы для последующего анализа.

## Предупреждение

Этот инструмент предназначен для образовательных и исследовательских целей. Не злоупотребляйте , соблюдайте правила использования сети Интернет и уважайте чужие ресурсы.

## Установка

1. Убедитесь, что у вас установлен Python версии 3.8 и выше.
2. Установите зависимости, используя команду `pip install -r requirements.txt`.

## Использование

1. Создайте файл со списком сайтов, каждый сайт должен быть указан в новой строке.
2. Запустите скрипт, указав путь к файлу со списком сайтов и, при необходимости, максимальное количество обрабатываемых URL-адресов:
    ```
    python main.py file.txt -m 50
    ```
    Здесь `file.txt` - это путь к файлу со списком сайтов, а `-m 50` указывает максимальное количество URL-адресов для обхода (по умолчанию 30).
3. Следуйте инструкциям в выводе программы.

## Важно!

1. Не злоупотребляйте скриптом и соблюдайте законы и правила использования сети Интернет.
2. При использовании скрипта будьте вежливы и уважайте чужие ресурсы.
3. Авторы скрипта не несут ответственности за неправомерное использование данного инструмента.

## Советы по безопасности

1. Убедитесь, что у вас есть разрешение на сканирование сайтов, которые вы собираетесь обрабатывать.
2. Не используйте скрипт для атак и нарушений безопасности.

## Сообщение об ошибке и поддержка

Если вы обнаружите ошибку или у вас есть предложения по улучшению скрипта, пожалуйста, создайте новый issue в репозитории.

## Лицензия

Этот проект лицензирован в соответствии с лицензией MIT.
