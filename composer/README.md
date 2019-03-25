# インストールとaws-sdkによるテーブル作成

お試しで、テーブル作成などを行う場合、
この階層で以下のコマンドを試すと良い


```
chmod +x install.sh
aws configure
composer install -g
php MoviesCreateTable.php
```

aws-cliのインストールがうまくいったという前提ではあるが
上記のコマンドで、Moviesというテーブルが作成される。
なお、aws configure において入力する内容は、ダミーで良い。
composerのインストールがされていない場合には、インストールを行うこと
