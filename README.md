# RemoconServant212_ex
USB接続 赤外線リモコンKIT 個人改造

## ■公式リンク
### USB接続 赤外線リモコンKIT | ビット・トレード・ワン
https://bit-trade-one.co.jp/BTOpicture/Products/005-RS/

### リポジトリ | Github
https://github.com/bit-trade-one/AD00020-USB_IR_Remote_Controller

## ■開発環境

## PICマイコンについて
### PICマイコン：PIC18F14K50

## IDE
### MPLAB v8 Microchip
https://www.microchip.com/en-us/development-tools-tools-and-software/mplab-ecosystem-downloads-archive

## コンパイラ
### コンパイラ C18 (評価版60日、DLに登録必要)
https://www.microchip.com/en-us/development-tool/SW006011

## Win10でビルドする際の注意点
・パスにマルチバイト文字が含まれているとプロジェクトを読み込まない  
・どのコンパイラ、リンカー等々がどこにあるか、という設定を行う（MCC18）  
・標準ライブラリのヘッダー、ライブラリの読み込み先がデフォルトでは"C:\MCC18"になっている  
→ 必要に応じて変更、MCC18のデフォルトインストール先と異なるため通常はパスの変更または追加が必要

## ■個人メモ
## メモ中
