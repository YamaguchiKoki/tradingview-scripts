# tradingview-scripts

TradingView 用 Pine Script 置き場。Pine Editor に貼り付けて使う。

## スクリプト一覧

| ファイル | 概要 | 想定チャート |
|---|---|---|
| [indicators/usdjpy-1h-30pips-move.pine](indicators/usdjpy-1h-30pips-move.pine) | 直近1時間で30pips以上の上昇/下落を検知してアラート | USDJPY 1分足 |

## アラート(プッシュ通知)の設定

1. 想定チャートを開き、インジケーターを追加
2. Alt+A でアラート作成 → 条件にインジケーターを選び「alert() 関数呼び出しのみ」
3. 通知で「アプリに通知」を ON(スマホの TradingView アプリにログインしておく)
