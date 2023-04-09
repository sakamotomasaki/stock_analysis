# stock_analysisの概要
株価データ分析のためのソースコードとデータです
## ソースコードの内容
### 株価データ分析の勉強用ソースコード
株価データ分析のためのサンプルソースコードです
#### stock1_chart.ipynb
- 株価データのチャート（chart）として、終値、移動平均、出来高をグラフ化します
#### stock2_index.ipynb
- 株価データの指標（index）として、MACD、RSI、ボリンジャーバンドのデータを作成してグラフ化します
#### stock2_mplfinance.ipynb
- mplfinanceを用いて、ローソク足をグラフ化します
#### stock3_mplfinance.ipynb
- mplfinanceを用いて、ローソク足をグラフ化します
#### stock4_ichmoku.ipynb
- 一目均衡表（ichimoku）のデータを作成してグラフ化します
#### stock5_backtest.ipynb
- 株価データに対して、事前に定義した売買ルールに基づくバックテスト（backtest）を行います
- ※ソースコードは完成していません
#### stock6_lstm.ipynb
- 株価データを用いて、予測モデルを構築します
- 予測モデルの構築には、RNN（再帰的ニューラルネットワーク）の１つの手法であるLSTM（lstm）を用います
#### stock7_rma.ipynb
- 株価データを用いて、予測モデルを構築します
- 予測モデルの構築には、重回帰分析（mra：Multiple Regression Anarysis）を用います
### 株価データ取得用のソースコード
#### get_data_stooq.ipynb
- stooqより株価データを取得します
#### get_data_yahoo.ipynb
- yahoo financeより株価データを取得するより株価データを取得します
## データの内容
### list
ETF、投資信託商品を一覧形式（list）としたデータです
#### list_etf.csv
- 海外ETFの商品一覧です
#### list_etf_jp.csv
- 国内ETFの商品一覧です
#### list_fund_jp.csv
- 国内投資信託（fund）の商品一覧です
### fund_jp
国内投資信託（fund）の基準価格推移のデータです
