# gitコマンド

* リポジトリのダウンロード

```
git clone [リポジトリURL]
```

* ローカルリポジトリの作成

```
git init
```

* インデックスに追加｜削除

```
git add [ファイルパス]
git reset [ファイルパス]
```

* ステータスの確認

```
git status
```

* リモートリポジトリ情報の追加｜確認

```
git remote add origin [GitHubのURL]
git remote -v
```

* コミット

```
git commit -m [コミットメッセージ]
```

* プッシュ｜プル

```
git push origin master
git pull origin master
```

* その他
  * [gitignoreについて](https://qiita.com/anqooqie/items/110957797b3d5280c44f)

<br>

# docker

* Docker Hubからイメージを取得

```
docker pull [イメージ名]
```

* コンテナの生成

```
docker run -d --name [生成するコンテナ名] [生成に利用するイメージ名] [実行するコマンド]
```

* コンテナに入る

```
docker exec -it [コンテナ名] [実行するコマンド]
```

* コンテナの起動｜停止

```
docker start [コンテナ名]
docker stop [コンテナ名]
```

* コンテナの削除

```
docker rm [コンテナ名]
```

* コンテナの確認

```
docker ps -a
```

* コンテナのイメージ化

```
docker commit [コンテナ名] [イメージ名]:[タグ名]
```

* イメージの削除

```
docker rmi [イメージ名]
```

* イメージの確認

```
docker images
```






