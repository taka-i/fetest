# 基本技術者情報の過去問のsql学習リポジトリ

# dockerでsqlite用のコンテナが起動できるようにしました

## sqlite用イメージのビルド
docker-compose build

## コンテナ起動
docker-compose up -d

## コンテナの起動の確認
docker ps
->fetest_sqlite_1が起動していることを確認する

## コンテナへ入ってbash起動
docker exec -it fetest_sqlite_1 /bin/bash
