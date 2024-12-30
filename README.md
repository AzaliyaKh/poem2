# Банк стихотворений

Проект представляет собой веб-приложение для парсинга, в котором отображаются лучшие авторы месяца и их произведения. [Сайт для парсина.](https://stihi.ru/)

## Основные функции

- **Лучшие авторы этого месяца**
- **Произведения автора**

## Технологии

- **Язык программирования**: Python 3.10
- **Библиотеки**:
  - `Flask` для разработки веб-интерфейса;
  - `BeautifulSoup` для парсинга HTML;
  - `sqlite3` для работы с базой данных;
  - `requests` для работы с HTTP-запросами.

### Предварительные требования

- Установленный Docker и Docker Compose.
- Установленный Python 3.8 (для запуска без Docker).

### Запуск с помощью Docker

1. Клонирование репозитория:

   ```bash
   git clone https://github.com/AzaliyaKh/poem.git
   cd app
   ```

2. Запуск приложения:

   ```bash
   ./build.sh
   ```

## Страницы сайта

### Главная страница: список лучших авторов текущего месяца
![Главная страница: список лучших авторов текущего месяца](ressdme_img/img1.png)
### Страница со стихотворениями автора
![Страница со стихотворениями автора](ressdme_img/img2.png)
