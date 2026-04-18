# phalcon-ecs-study
# phalcon-ecs-study

PHP の Phalcon 系システムを意識した、ECS / Aurora / GitHub Actions 学習用プロジェクトです。

## ローカル起動

```bash
docker compose up -d --build
```

ブラウザで以下を開きます。

```text
http://localhost:8080
```

## 停止

```bash
docker compose down
```

## ログ確認

```bash
docker compose logs -f
```

## ディレクトリ構成

```text
phalcon-ecs-study/
├── docker-compose.yml
├── .gitignore
├── app/
│   └── public/
│       └── index.php
├── Dockerfile.httpd
├── Dockerfile.php
└── README.md
```