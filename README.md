# php-docker1

コンテナを使って PHP を動かす最初の 1 歩。

Alpine で php-fpm(8.5) で nginx

## 実行

```sh
docker compose up -d
```

で <http://localhost:9090> で`phpinfo()`が見える。

```sh
docker compose down
```

で終了。

### justfile つけました

```sh
just dev  # ログ出しながら実行
just down # 終了
#
just start # バックグラウンドで実行
just logs  # ログ出す
just down  # 終了
```

[just](https://github.com/casey/just) は apt などでインストールしてください。
