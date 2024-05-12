# Развертывание ML модели в Docker.

1. Создаем образ в докере.
---------------------
.. code-block::

    docker build -t image_name .

3. Запускаем контейнер.
----------------
.. code-block::

    docker run --name container_name -p 8000:8000 image_name

4. Получаем ссылку в терминале.
----------------------
INFO:     Uvicorn running on http://0.0.0.0:8000

Use this url in chrome to see the model frontend;
use http://0.0.0.0:8000/docs for testing the model in the web interface.
