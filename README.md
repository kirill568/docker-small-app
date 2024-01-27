## Как запустить  
1. Установите [docker](https://docs.docker.com/engine/install/)
2. Выполните команду `docker build -t test_fast_api_app:v1 .`
3. Выполните команду `docker run -p 9000:9000 test_fast_api_app:v1`
4. Откройте браузер по адресу `http://127.0.0.1:9000`