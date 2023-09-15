# PaintChat_inC

## 概要
PaintChat_inCは、情報ネットワークIIの授業で開発されたクライアント・サーバ型のリアルタイム手書きチャットプログラムです。

## 環境構築
以下のコマンドを使用して、必要なライブラリをインストールできます。

```bash
# 必要なライブラリをダウンロード
sudo apt update
sudo apt install build-essential
sudo apt install libx11-dev

# コンパイル方法
gcc -o [output_filename] [input_filename] -lX11
```
# 機能

## 開発済みの機能
- テキストとフリーハンドによるメッセージの書き込み
- マルチコネクションのサポート
- 発言者の表示
- ディスプレイのサイズ変更時の再描画（サーバーサイドのみ）

## 追加したい機能
以下の機能を将来の開発で追加予定です：
- 参加者ごとの色分け
- 動的なメモリの確保
- 消しゴムツールの追加


