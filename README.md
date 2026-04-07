# Simple GPS Logger

ブラウザの[位置情報API](https://developer.mozilla.org/ja/docs/Web/API/Geolocation_API)を使用して取得したデータを[NMEA 0183](https://ja.wikipedia.org/wiki/NMEA_0183)の形式に変換します。

## 公開ページ
https://misogohei.github.io/nmealog/
取得した位置情報はブラウザ上で処理され外部へは送信しません。

## 機能

- 位置情報をGGA/RMCセンテンスへ変換
- 変換結果の保存
  - クリップボード
  - ファイル
- 最新位置情報の表示
- 取得の一時停止/再開
- 画面自動ロックOFF

## 制限

取得できないデータは仮の値が固定で設定されます。
- 衛星数(12)
- ジオイド高さ(36.7071)
- 測位ステータス(1)
- など

