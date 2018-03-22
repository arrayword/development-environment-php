# PHP開発環境
Vagrantを使用したPHPの開発環境です。

## サーバー構成
各製品のバージョンは2018/03/28時点で確認した内容を記載しています。

### 全サーバー共通
* CentOS 7.4

### WEBサーバー
* Apache httpd 2.4.6
* PHP 7.2.3

### DBサーバー
* MariaDB 10.2

### CIサーバー
* Python 2.7.5
* Ansible 2.4.2.0
* Java 1.8.0_161 (OpenJDK)
* Jenkins 2.107.1

### SCMサーバー
* Git 1.8.3.1

## 仮想マシンホストの必須要件
* Vagrant 2.0.2
* VirtualBox 5.2.6

## 使い方
1. Vagrant 2.0.2をインストールする。
1. VirtualBox 5.2.6をインストールする。
1. このプロジェクトをクローン
1. "provisioning/inventories/local/group_vars"の値をクローンした環境に合わせて設定
1. プロジェクトのルートディレクトリで"vagrant up"コマンドを実行

