# play-framework-docker
Docker 上で Play Framework の環境を作ったのでメモ

# Installation

```sh
$ docker-compose up -d
$ docker-compose exec app bash
```

# Create Play App
`myapp` というアプリを作成する場合

## Java

```sh
$ activator new myapp play-java
```

## Scala

```sh
$ activator new myapp play-scala
```

# Run

```sh
$ activator run
```

アプリケーションは `localhost:9000` で公開される．

サーバを停止するには，`[Ctrl]+[d]`を入力する．

#  参考サイト

- [Play 2.4 ドキュメント](https://www.playframework.com/documentation/ja/2.4.x/Home)
