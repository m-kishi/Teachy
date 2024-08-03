# Teachy

### 環境構築
コンテナのビルド＆起動
```
$ docker-compose up -d --build
```

teachy-app に接続
```
$ docker exec -it teachy-app /bin/bash
```

rails の初期設定
```
/app# bundle install
/app# rails db:create
/app# rails db:migrate
```
