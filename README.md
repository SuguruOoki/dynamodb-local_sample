# 使い方

```
git clone git@github.com:SuguruOoki/dynamodb-local_sample.git
cd dynamodb-local_sample
docker-compose up -d --build
```
上記コマンドを実行するのみ

# 注意

dynamodb という名前のサービス名が被っていると、立ち上げに失敗するので、
そこは適宜docker-compose.ymlファイルの名称などを調整すること
