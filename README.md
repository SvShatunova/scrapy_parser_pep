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

- Python
- Scrapy

##### Автор

[Светлана Шатунова](https://github.com/SvShatunova)
