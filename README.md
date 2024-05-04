# bun-template
DockerによるBunの開発環境構築用のテンプレート

## 環境構築
1. コンテナのビルド・起動
```
docker compose up -d --build
```

2. bunのインストール確認
```
docker compose exec web bun -h
```
