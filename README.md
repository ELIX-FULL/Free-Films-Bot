# Free-Films-Bot

Бот, позволяющий искать фильмы по названию (используя информацию с Кинопоиска). Также бот умеет рекомендовать фильмы, если вы не знаете, что посмотреть.

---


## Использование

  Использование
  **Поиск фильма**
  Введите название фильма, и бот найдет фильм из Kinopoisk.
  
  **Рекомендации**
  Если вы не знаете, что посмотреть, нажмите кнопку «🌟Не знаешь, что посмотреть? Кликай!», и бот предложит вам интересный фильм на основе данных Кинопоиска.

## Установка

1. **Клонируйте репозиторий:**
   ```bash
   git clone https://github.com/ELIX-FULL/Free-Films-Bot.git

2. **Перейдите в папку с проектом:**
   ```bash
   cd Free_Films


3. **Установите необходимые зависимости:**
   ```bash
   pip install -r requirements.txt

4. **Настройка**
Откройте и отредактируйте файл config.py, указав в нём свои данные:
config.py

  token = 'ТОКЕН_ТГ_БОТА'        # Ваш токен бота
  
  chan = 'КАНАЛ_ДЛЯ_ПОДПИСКИ'   # Канал, на который нужно подписаться
  
  ID_ADM = [ID_АДМИНОВ]         # Список ID администраторов
  

6. Запуск
После указания всех настроек в config.py, запустите бота:
  python bot.py
