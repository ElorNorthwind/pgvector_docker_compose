# YAML file to run PostgreSQL with pgvector and an instance of pgAdmin in docker.

1. add .env file with your secrets (see .env_example)
2. launch the containers with:

```bash
docker compose up
```

3. pgAdmin will be avaliable at [port 5050](http://localhost:5050/browser/)
4. remember to set hostname to postgres (or whatever is your docker network is called), not localhost
