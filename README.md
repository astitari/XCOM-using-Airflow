How to run airflow:
1. Create directory `dags`, `logs` and `plugins`. In this repo, you just need to make `logs` and `plugins` since `dags` is already filled with my python script.
2. Run `docker-compose up`
3. You can see the airflow in webserver through `localhost:8080` in your browser.
4. Login through with username `airflow` and password `airflow`.
5. Choose your dags files to run.