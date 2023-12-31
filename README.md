# plusコマンド


![test](https://github.com/tougokataita/robosys2022/actions/workflows/test.yml/badge.svg)

* 標準入力から読み込んだ数字を足す。
* 足した数字から平均を求める。
* 足した数字が奇数,偶数かを判別する。
* 足した数字が素数か判別し、素数なら素数と出力する。

## インストール
* 下記のコマンドでrobosys2023 リポジトリのコピーがローカルのディレクトリに作成されます。

 ```
git clone git@github.com:tougokataita/robosys2023.git
```

## 実行方法
* ディレクトリ(robosys2023)に移動し plus を実行してください。
このプログラムは1~任意の数字までを足し合わせるプログラムです。

```
seq n | ./plus
``` 

  nの部分を任意の数字に変更して実行してください。

* 実行例 1
```
seq 2 | ./plus

0 + 1 = 1
1 + 2 = 3

1 ~ 2の合計 : 3
平均値 : 1.5
奇数
素数
```

* 実行例2
```
seq 7 | ./plus

0 + 1 = 1
1 + 2 = 3
3 + 3 = 6
6 + 4 = 10
10 + 5 = 15
15 + 6 = 21
21 + 7 = 28

1 ~ 7の合計 : 28
平均値 : 4.0
偶数
```

## テスト環境
* Ubuntu20.04 
* Python
* テスト済みバージョン: 3.7 ~ 3.10
## 著作権
* このソフトウェアパッケージは，3条項BSDライセンスの下，再配布および使用が許可されます。
* このパッケージのコードは，下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです。
* [ryuichiueda/my_slides/robosys_2022](https://github.com/ryuichiueda/my_slides/blob/master/robosys_2022/lesson4.md)
* © 2023 Tougo Kataita

