【立ち上げ方】
docker-compose up 　

でdockerコンテナを起動しバックグラウンドモードにする。
お手元のブラウザに”127.0.0.1:8888”を検索し実行すると、
workdir直下のリソースがマウントされた状態でnotebookを表示される。

【ボリュームのマウント】
srcフォルダに利用したいcsvファイルなどをいれると読み込むこともできる。

【ライブラリのインストール】
requirements.txtに任意のライブラリを指定。
その後、”docker exec -it notebook bash" でコンテナに入ったのちにpip install を行う

https://qiita.com/hgaiji/items/edf71435d0565257f980