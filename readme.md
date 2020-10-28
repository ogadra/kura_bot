## 概要
指定した時間帯にEPARKでくら寿司の当日予約の空きがあるかを確認し、
空きが見つかったら音を鳴らして教えてくれるbotです。

## 使い方
1. 予約する店舗を決めます
1. EPARKでの、その店舗のURL末尾の数字をメモします。（くら寿司池袋東口店の場合、「110202」。）
1. checker.pyの後半にある、設定の日付と検索したい時間帯のリスト、store_idを書き換えます。
1. pythonでchecker.pyを実行します。

## checker.pyの実行の方法
1. （初回のみ）`pip install -r requirements` を実行し、依存パッケージをインストールします。
1. `python checker.py`を実行すると、botが起動します。
1. botの起動中に指定した時間帯で空きを発見すると、音がなります。（音量注意）