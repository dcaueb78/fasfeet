rodar como dev: yarn dev
rodar debug mode: yarn dev:debug

criar container postgres: docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres

rodar container postgres: docker start database