# plusコマンド
![test](https://github.com/ryuichiueda/robosys2022/actions/workflows/test.yml/badge.svg)

## 機能
* 標準入力から読み込んだ数字を足す。

## ダウンロードの手順
* Ubuntu18.04をダウンロード

## インストールの手順
* Ubuntu内でgitが入っていない場合、次のコードを入力しインストール  
  `sudo apt install git`  
* Ubuntuで次のコードを入力  
  `git clone https://github.com/SoichiroS1066/robosys2022`  
## 起動の手順
* インストールの手順を終えたら次のコードを入力  
  `cd ~/robosys2022`
* 数値を読み込ませて足し算をする ※実行については使用例で説明

## 使用例
* 1 ～ 2 を足したい時
→ seq 2 | ./plus
   3
* 2 ～ 5 を足したい時
→ seq 2 5 | ./plus
  14

## 必要なソフトウェア
* Python 3.7～3.10

## テスト環境
* Ubuntu18.04

## 著作権に関して
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです。
	* [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* © 2022 Soichiro Suzuki
##
* このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されます。
