# DockerでNext.js環境構築

## Dockerビルド
docker-compose build

## create-next-appコマンドをインストール
docker-compose run --rm app npm install create-next-app

## create-next-appコマンドを実行
docker-compose run --rm app npx create-next-app [プロジェクト名]

### ※TypeScriptの場合
docker-compose run --rm app npx create-next-app [プロジェクト名] --ts

## Docker立ち上げ
docker-compose up -d