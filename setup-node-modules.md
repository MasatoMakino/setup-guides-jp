# node modulesのインストール

Visual Studio Codeを起動し、作業フォルダーを開きます。

![](https://www.evernote.com/l/AAkxzTMVKuhLUaARb5o73A3vXVdBVB_gxQIB/image.png)

次にメニューバーからターミナルを開きます。

![](https://www.evernote.com/l/AAn2imSSHXFLpYnOXiTXZessAGhDmHkIjp0B/image.png)

![](https://www.evernote.com/l/AAlhpeUMRM1LyooN3JxkbVl3eGoVVkVM0UgB/image.png)

ターミナルで以下のコマンドを実行します。コマンドをコピー&ペーストして実行してください。

    npm ci

このコマンドで、開発環境に必要なソフトウェアがダウンロードされます。

> **Warning**
> 
> 開発環境でnode modulesのセットアップを行う際に、`npm install`コマンドは使用してはいけません。必ず`npm ci`コマンドを使用してください。
> 
> `npm install`コマンドは`package-lock.json`ファイルの内容を上書きします。そのため、node modulesの一貫性を損なう場合があります。`npm install`コマンドはモジュールの追加、削除、更新があった時のみ使用してください。
