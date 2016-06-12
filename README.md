# hubot
slackでbotを作ってみる。

開発には以下６つのモジュールが必要らしい。
* Node.js
* npm
* hubot
* yo
* generator-hubot
* coffee-script

## 導入手順
まず`apt-get`でnodejsとnpmをインストールします。

```
$ sudo apt-get install -y nodejs npm
```
次にn packageを導入
```
$ sudo npm cache clean
$ sudo npm install n -g
```
最後にn packageを使ってnodeをインストールします。
```
$ sudo n stable
$ sudo ln -sf /usr/local/bin/node /usr/bin/node
```
バージョンの確認
```
$ node -v
v6.2.1
```
最初に入れたnodejsとnpmは古いので削除します。
```
$ sudo apt-get purge -y nodejs npm
```
