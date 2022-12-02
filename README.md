# robosys2022
![test](https://github.com/Yoshino0304/robosys2022/actions/workflows/test.yml/badge.svg)
* ロボットシステム学の練習リポジトリ
* 授業での学習内容が含まれています.

# plusコマンド
入力した値を足し算するプログラムです.

# 動作手順
1. GithubのサイトでcodeからSSHへ移動し, SSH keyをコピーする. 
1. ``` $ git clone git@github.com:Yoshino0304/robosys2022.git```
1. 実行する. 
    
* 実行例1:数字のみのファイルを作成する方法.

   ```$ seq 5 > <ファイル名>```  などでファイルを作成する.

   ```$ ./plus < <ファイル名>```で実行する.

* 実行例2:ファイルを作成しない方法.

   ```$ seq 5 | ./plus```  で実行する. 　

# 必要なソフトウェア
* Python 3.7～3.10

# 動作確認済み環境
* Ubuntu 22.04.1LTS 

# ライセンス
 * このソフトウェアパッケージは，3条項BSDライセンスの下，再頒布および使用が許可されます．
 * © 2022 Taiki Yoshino
