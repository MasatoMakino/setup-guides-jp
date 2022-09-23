# node.jsのインストール

## node.jsとは

node.jsは、JavaScriptをPC上でネイティブアプリケーションとして実行するためのソフトです。

## ダウンロードとインストール

[公式サイト](https://nodejs.org/ja/)からインストーラーをダウンロードします。

![](https://www.evernote.com/l/AAl5BI110RhDQ7XHB8krSA27xnkCp3v6gmAB/image.png)

開発環境にはLTS版を使用します。ダウンロードが完了したら、インストーラーを実行してください。

## 動作確認

node.jsのインストールが正常に完了しているか確認します。

### ターミナルを起動する

まず、Visual Studio Codeを起動し、メニューバーからターミナルを開きます。

![](https://www.evernote.com/l/AAn2imSSHXFLpYnOXiTXZessAGhDmHkIjp0B/image.png)

![](https://www.evernote.com/l/AAlhpeUMRM1LyooN3JxkbVl3eGoVVkVM0UgB/image.png)

次に、ターミナルに以下のコマンドを入力します。コマンドをコピー&ペーストしてください。

```bash
node --version
```

バージョン番号がターミナルに表示されれば、インストールは成功です。

```bash
v16.17.0
```

node.jsと同時にインストールされる`npm`のバージョンも確認します。

```bash
npm --version
```

バージョン番号が表示されれば、インストールは成功です。

```bash
8.14.0
```
