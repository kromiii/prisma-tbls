# 使い方

## Databaseの起動

```
docker compose up -d
```

で localhost:5432 に PostgreSQL が起動します。

## Migrationの実行

```
yarn install
yarn prisma migrate dev
```
