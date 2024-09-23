
### Как запустить и проверить ДЗ
1. Клонирование репозитория
``` git clone https://github.com/BogruAKVD/python_backend_course.git```
2. Перейти в папку с ДЗ1
``` cd hw1 ```
3. Установка зависимостей
``` pip install -r requirements.txt ```
4. Запуск сервера на одном терминале
``` uvicorn main:app ```
5. Тестирование на другом терминале
``` pytest test_homework_1.py ```