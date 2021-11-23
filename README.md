# DockerでNext.js環境構築

## create-next-appコマンドをインストール
docker-compose run --rm node npm install create-next-app

## create-next-appコマンドを実行
docker-compose run --rm node npx create-next-app [プロジェクト名]

## Docker立ち上げ
docker-compose up -d