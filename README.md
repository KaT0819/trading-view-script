# TradingView Pineスクリプト集

このリポジトリは、自作のTradingView用Pineスクリプトを管理する場所です。

## ディレクトリ構成

```
trading-view-script/
├── src/
│   ├── indicators/     # インジケーター
│   ├── strategies/     # ストラテジー
│   └── libraries/      # 共通ライブラリ
├── assets/             # スクリーンショットなどの画像
└── README.md           # このファイル
```

## スクリプト一覧

### インジケーター (Indicators)

*   **[My Indicator 1](./src/indicators/my_indicator_1.pine)**
    *   単純移動平均線を表示するインジケーターです。

### ストラテジー (Strategies)

*   **[My Strategy 1](./src/strategies/my_strategy_1.pine)**
    *   単純移動平均線のクロスオーバーでエントリー/クローズするストラテジーです。

### ライブラリ (Libraries)

*   **[Common Functions](./src/libraries/common_functions.pinescript)**
    *   共通で利用する関数をまとめたライブラリです。

## 利用方法

1.  使いたい`.pine`ファイルを開きます。
2.  中のコードをすべてコピーします。
3.  TradingViewでPineエディタを開きます。
4.  コードを貼り付け、「チャートに追加」をクリックします。