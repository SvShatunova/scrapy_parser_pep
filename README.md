# scrapy_parser_pep

## Описание

Парсер работает на асинхронном фреймворке Scrapy, собирает актуальную информацию о версиях PEP и сохраняет результат парсинга ив формате CSV

Список поддерживаемых сайтов:

- https://peps.python.org/

### Инструкция по запуску

**Клонируйте репозиторий:**

- git clone ...

**Установите и активируйте виртуальное окружение:**

- python -m venv venv (python3 -m venv venv)

- source venv/Scripts/activate (source venv/bin/activate)

**Установите зависимости из файла requirements:**

- pip install -r requirements.txt

**Из корневой директории запустите парсер:**

- scrapy crawl pep

#### Технологии

![Python](https://img.shields.io/badge/python-3.9-blue?logo=python)
![Scrapy](https://img.shields.io/badge/scrapy-2.5.1-brightgreen?style=flat&logo=appveyor&logoColor=green&logoSize=auto&labelColor=black&color=blue&cacheSeconds=%203600)

##### Автор

[Светлана Шатунова](https://github.com/SvShatunova)
