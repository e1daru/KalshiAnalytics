docker run -d \
 --name pg \
 -e POSTGRES_PASSWORD=kek \
 -e POSTGRES_USER=eldar \
 -e POSTGRES_DB=kalshi \
 -p 5432:5432 \
 -v pgdata:/var/lib/postgresql/data \
 postgres:16
