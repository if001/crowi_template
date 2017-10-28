# crowiのテンプレート
公式を参考
https://github.com/crowi/docker-crowi

## 構成
 - nginx
   リバースプロキシ
   設定ファイルと、ログはホストにマウント
 - crowi
    ほぼそのまま、DBとPASS_SEEDは外部にマウント 


## dockerのインストール
### dockerのインストール
かえるとこはかえる
```
sudo curl -o /usr/local/bin/jq -L https://github.com/stedolan/jq/releases/download/jq-1.5/jq-linux64 && sudo chmod +x /usr/local/bin/jq
curl -fsSL get.docker.com | bash
```


### docker-composeのインストール
バージョンはよしなに
```
curl -L https://github.com/docker/compose/releases/download/1.14.0/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose
chmod +x /usr/local/bin/docker-compose
```

