# docker-sample

##立ち上げ方

###コマンドプロンプトからこのファイルに移動

- 初回起動
```
$ docker-compose up -d --build 
```

- 起動
```
$ docker-compose up -d
```

- コンテナ接続
```
$ docker-compose exec コンテナ名 bash
ex)
$ docker-compose exec mysql bash
```
コンテナからぬける
Ctrl + D  又は exit

- コンテナを終了する
```
$ docker-compose down
```

- コンテナを再起動する
```
$ docker-compose restart
```

- コンテナの状態をみる
```
$ docker-compose ps
```

- コンテナのlogをみる
```
$ docker-compose logs
```
