# Horoscope_Trudkov
Данный API позволяет распарсить сайт с гороскопами - goroskop365.ru

Рабочий функционал: Узнать гороскоп на определённый день\неделю\месяц пмо знакам Зодиака

Что нужно сделать что бы сайт заработал:
1.Создать виртуальную среду

 $ python -m venv env
Чтобы активировать виртуальную среду с именем env, используйте следующие команды:

 в Windows — env\Scripts\activate.bat

 в Linux и MacOS — source env/bin/activate

Чтобы деактивировать введите deactivate

2.Установите следующие библиотеки

 $ pip install requests Библиотека requests позволяет очень легко отправлять запросы.

 $ pip install bs4 Beautiful Soup (bs4) – библиотека Python для извлечения данных из файлов HTML и XML.

 $ pip install flask  - микрофреймворк Python. Он помогает создавать масштабируемые и безопасные веб-приложения.

 $ pip install flask-restx - позволяет создавать API с помощью документации Swagger.

 $ pip install python-decouple - возможность использовать переменные среды проекте.

3.Запустить файл который поможет нам запустить сервер Flask

 $ python main.py   
