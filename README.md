# php-docker1

コンテナを使ってPHPを動かす最初の1歩。

Alpine で php-fpm で nginx

## 実行

```sh
docker compose up -d
```

で <http://localhost:9090> で `phpinfo()` が見える。

```sh
docker compose down
```

で終了。
