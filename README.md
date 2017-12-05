https://github.com/nakalab/AutomatedCropsIncubator.git
以下の下準備が必要
・IncubatorListenerディレクトリ	paho-mqtt
photosディレクトリを作成
sqlInterfaceは外部ライブラリで参照されているが、そのライブラリはgit上にはない 

・Flaskディレクトリ Flask pygal


IncubatorListener   sensorListener.pyを実行　MQTTListenerが立ち上がり、Incubatorから送られる画像を取得できたことを確認
Flask /mySite/script.pyを実行　127.0.0.1:5000でWebページが立ち上がったことを確認


現システムに機械学習機能はなし　plantCVディレクトリは本家plantCVリポジトリのモノと酷似
データの受け渡しはMQTTである必要はない





タスク
IncubatorListenerからFlaskへのデータの受け渡しの確認
openAGというワードで先行事例調査
研究の方向性を決める








