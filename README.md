■実装環境
・Macbook（2017年モデル）
・Python 3.7.0

■概要
・“ユーザーローカル顔認識API”を使い、PCWEBカメラで撮影した
顔画像を年齢・性別分析できる簡易WEBアプリを作成。 　※Flaskでローカルで起動。

▼ユーザーローカル
顔認識API https://face-ai.userlocal.jp/

▼使用ライブラリ
・openCV
　∟PCWEBカメラ立ち上げでの撮影。（＝分析元素材撮影）

■各Pythonファイル説明　※HTML・CSSは割愛
・userlocal.py
　∟ユーザーローカル顔認識APIの実行コード。

・opencv3.py
　∟opencv使っての『PCWEBカメラで顔画像撮影』、
  『指定ディレクトリへ撮影画像保存』実行コード。

・opentest.py
　∟Flask立ち上げコード。
