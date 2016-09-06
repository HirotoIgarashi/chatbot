# chatbot
## 開発環境
### OS
バージョンの確認
```
$ cat /etc/lsb-release
DISTRIB_ID=Ubuntu
DISTRIB_RELEASE=16.04
DISTRIB_CODENAME=xenial
DISTRIB_DESCRIPTION="Ubuntu 16.04.1 LTS"
```
アーキテクチャの確認
```
$ arch
x86_64
```
### Python仮想環境
pyvenvのインストール
```
$ sudo apt install python3-venv
```
仮想環境の作成。chatbotEnvという名前の環境を作成する。
```
$ pyvenv chatbotEnv
```
アクティベートの実行
```
$ source chatbotEnv/bin/activate
```
仮想環境から抜ける
```
$ deactivate
```
### 各種ライブラリ
NLTK(Natural Language Tool Kit)のインストール
```
$ sudo pip3 install -U nltk
...
Successfully installed nltk-3.2.1
```
