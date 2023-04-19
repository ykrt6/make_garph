# make_graph

これはPythonでグラフ作成をwebアプリです。

### ファイル構成

- function
    - web_app_graph.py : グラフの作成を行う
- init
    - init.csv : グラフを作成の各種設定項目 (このファイルの中身を変えるとフォントなどを変更できます)
- sample_data : サンプルデータです
    - data.csv
    - log.csv
- database.db : ユーザに関するデータベース
- requirements.txt : 各種モジュールバージョン
- web_app_main.py : webアプリの動作設定

### 使い方

基本的にはログインをし、データファイルをアップロードと詳細設定を行って更新ボタンをクリックするとグラフが表示されます。
もし、ローカル上でこのプログラムを動かす場合は以下のコマンドを入力して下さい。

~~~ 
streamlit run web_app_main.py
~~~