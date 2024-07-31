# Парсер Бундестага

Этот проект представляет собой асинхронный парсер для извлечения данных о членах Бундестага с официального сайта федерального парламента Германии.

## Описание

Парсер использует библиотеки Python для асинхронного веб-скрапинга и анализа HTML, чтобы собирать информацию о депутатах Бундестага. Он извлекает имена депутатов, их партийную принадлежность и ссылки на их социальные сети.

## Требования

Проект использует следующие библиотеки Python:

- aiohttp==3.9.5
- aiosignal==1.3.1
- attrs==23.2.0
- beautifulsoup4==4.12.3
- frozenlist==1.4.1
- idna==3.7
- multidict==6.0.5
- soupsieve==2.5
- yarl==1.9.4

## Установка

1. Клонируйте репозиторий:Спасибо за предоставленный код. Я обновлю README, чтобы он более точно отражал функциональность вашего парсера Бундестага. Вот обновленный вариант:
markdownCopy# Парсер Бундестага

Этот проект представляет собой асинхронный парсер для извлечения данных о членах Бундестага с официального сайта федерального парламента Германии.

## Описание

Парсер использует библиотеки Python для асинхронного веб-скрапинга и анализа HTML, чтобы собирать информацию о депутатах Бундестага. Он извлекает имена депутатов, их партийную принадлежность и ссылки на их социальные сети.

## Требования

Проект использует следующие библиотеки Python:

- aiohttp==3.9.5
- aiosignal==1.3.1
- attrs==23.2.0
- beautifulsoup4==4.12.3
- frozenlist==1.4.1
- idna==3.7
- multidict==6.0.5
- soupsieve==2.5
- yarl==1.9.4

## Установка

1. Клонируйте репозиторий: git clone  https://github.com/Aliaksandrsw/parser_bundestag.git
2. Перейдите в директорию проекта
3.  Установите зависимости: pip install -r requirements.txt

## Использование

Для запуска парсера выполните следующую команду: python main.py

## Функциональность

Парсер выполняет следующие действия:

1. Асинхронно получает список URL-адресов всех депутатов с пагинированных страниц.
2. Для каждого депутата извлекает следующую информацию:
   - Имя
   - Партийная принадлежность
   - Ссылки на социальные сети
3. Сохраняет собранные данные в JSON-файл.
