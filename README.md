# docker-python-demo
Dockerコンテナでlistenするアドレスによるアクセス可否の確認デモ

## ローカル環境立ち上げる
```shell
docker-compose up
```

## ローカル環境止める
```shell
docker-compose down
```

## ブランチ情報
- main
  - 動作する環境(0.0.0.0でlisten)
- demo/empty-reaponse
  - 動作しない環境(127.0.0.1でlisten)
