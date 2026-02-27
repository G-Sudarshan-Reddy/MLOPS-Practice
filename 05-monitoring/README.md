1. Setup the docker-compose
2. Setup the config
3. Start the build

    -> docker-compose up --build

    Incase the build failed and cached follow the below
    ->docker compose down
    ->docker compose down -v
    ->docker compose up --force-recreate