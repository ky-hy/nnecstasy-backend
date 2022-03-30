# nnecstasy-backend

nnecstasy のバックエンドリポジトリです。

# 必要ツール

docker: 20.10.11
docker-compose: 1.29.2

# 開発手順

```sh
# git clone(サブモジュールも同時にclone)
$ git clone --recursive https://github.com/ky-hy/nnecstasy-backend.git
$ cd ./nnecstasy-backend
# 以下のコマンドを実行後.envに値を代入
$ cp .env.example .env
# コンテナ起動
$ docker-compose up -d --build
# expressのログの確認
$ docker-compose logs -f express
```

express のロカールサーバーの URL は[http://localhost:3000/](http://localhost:3000/)です
