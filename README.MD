# 使い方
1. 公式サイトからDockerをDownloadする。
[Docker公式サイト](https://www.docker.com/ja-jp/)

2. ターミナルを開き、docker-mysqlまでcdする。

3. 以下のコマンドを打つ
- イメージのビルド
```bash
Docker-Compose build
```
- コンテナの作成
```bash
Docker-Compose up -d
```
- 起動したコンテナにログイン
```bash
docker exec -it mysql bash -p
```
- 一度mysqlにアクセス
```bash
mysql -u root -p -h 127.0.0.1
```
- パスワードは1234
