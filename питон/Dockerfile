# Используем последний официальный образ Python
FROM python:latest

# Устанавливаем рабочую директорию внутри контейнера
WORKDIR /app

# Копируем файл test.py в рабочую директорию контейнера
COPY test.py /app

# Запускаем Python-скрипт
CMD ["python", "test.py"]
