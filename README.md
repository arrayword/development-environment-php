# PHP開発環境
Vagrantを使用したPHPの開発環境です。

## 仮想マシンホストの必須要件
* Vagrant 2.0.2
* VirtualBox 5.2.6

## 使い方
1. Vagrant 2.0.2をインストールする。
1. VirtualBox 5.2.6をインストールする。
1. このプロジェクトをクローン
1. "provisioning/inventories/local/group_vars"の値をクローンした環境に合わせて設定
1. プロジェクトのルートディレクトリで"vagrant up"コマンドを実行

