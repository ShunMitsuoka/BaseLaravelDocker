# MSBoxBaseLaravelDocker

BaseLaravelDockerはLaravelプロジェクト作成用のDocker構成になります。
pull後はローカルブランチを作成してお使いください。

```
cp .env.example .env
```

DBの設定を任意に変更

## イメージ作成＆コンテナ作成＆起動

```
docker-compose up -d
```

## イメージを変更した場合

```
docker-compose build
docker-compose up -d
```