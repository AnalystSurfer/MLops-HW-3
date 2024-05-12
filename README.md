# Развертывание ML модели в Docker.

1. Создаем образ в докере.
---------------------

    docker build -t image_name .

3. Запускаем контейнер.
----------------

    docker run --name container_name -p 8000:8000 image_name

4. Получаем ссылку в терминале.
----------------------

    Uvicorn running on http://0.0.0.0:8000


