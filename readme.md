【立ち上げ方】
docker-compose up -d

でdockerコンテナを起動しバックグラウンドモードにする。
お手元のブラウザに”127.0.0.1:8888”を検索し実行すると、
workdir直下のリソースがマウントされた状態でnotebookを表示される。

【ボリュームのマウント】
srcフォルダに利用したいcsvファイルなどをいれると読み込むこともできる。

【ライブラリのインストール】
requirements.txt に任意のライブラリを書き、
gitlabにてターミナルを起動し、

$cd work
$pip install -r requirements.txt 

を実行。

参考文献
https://qiita.com/hgaiji/items/edf71435d0565257f980
