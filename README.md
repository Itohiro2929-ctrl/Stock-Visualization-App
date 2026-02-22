# 米国株価可視化アプリ

Streamlitを用いて、米国主要IT企業（GAFAM + Netflix）の株価データを取得し、インタラクティブな折れ線グラフで可視化するWebアプリケーションです。

## 機能 (Features)

* **表示日数の指定**: スライダーを使って、過去1日〜50日間の間で表示したい期間を自由に設定できます（デフォルト：20日）。
* **株価の範囲指定**: Y軸（株価 - USD）の表示範囲をスライダーで0.0〜3500.0の間で絞り込むことが可能です。
* **企業の選択**: マルチセレクトボックスから、グラフに表示したい企業を自由に選択・除外できます。
* **データテーブル表示**: 取得した株価データ（終値）をテーブル形式で確認できます。
* **インタラクティブなグラフ**: Altairによる美しい折れ線グラフで、視覚的に株価の推移を比較できます。

## 対象企業 (Supported Companies)

* Apple (`AAPL`)
* Meta (`META`)
* Google (`GOOGL`)
* Microsoft (`MSFT`)
* Netflix (`NFLX`)
* Amazon (`AMZN`)

## 必要要件 (Requirements)

Python環境と、以下のライブラリが必要です。詳細なバージョンはリポジトリ内の `requirements.txt` をご参照ください。

* `streamlit`
* `pandas`
* `yfinance`
* `altair`

## インストールと実行方法 (Installation & Usage)

1. **リポジトリのクローン**（またはファイルのダウンロード）
   ```bash
   git clone [https://github.com/あなたのユーザー名/リポジトリ名.git](https://github.com/あなたのユーザー名/リポジトリ名.git)
   cd リポジトリ名