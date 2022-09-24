# ソースコードのクローン

GitHub上に公開されているソースコード一式を、開発環境にクローンします。GitHubのリポジトリページからURLをコピーします。

![](https://www.evernote.com/l/AAlWHdGVdXpEXr_zz1K9aUKC1GuXocPyOTAB/image.png)

## ローカルリポジトリの作成

次に、SourceTreeを起動し、リポジトリブラウザを表示します。

![](https://www.evernote.com/l/AAm6W0dJgwNPsrzppCm5CRBPSyWlMN6W8lkB/image.png)

![](https://www.evernote.com/l/AAmwC6d6u51AZI-ktxYa7f8Arb12Llzi-hwB/image.png)

リポジトリブラウザの「新規…」→「URLからクローン」を選択し、先ほどコピーしたGitHubのURLをペーストします。これで編集履歴を含めた、完全なソースコードのコピーを取得できます。

![](https://www.evernote.com/l/AAlSKULsklZAKorJvSg-LlIGqFzoO-P4Bu0B/image.png)

PC上にあるGitリポジトリを「ローカルリポジトリ」、Gitホスティングサービス上にあるGitリポジトリを「リモートリポジトリ」と呼びます。開発環境では、クローンしたローカルリポジトリを操作します。

## リモートリポジトリとの接続解除

この状態では、GitHubのリモートリポジトリと接続が保たれています。リモートリポジトリを変更しようとすると、認証に失敗してエラーになります。また、リモートリポジトリが変更されると追従します。

エラーが何度も表示されると面倒だ、という場合は以下の手順でリモートリポジトリとの接続を解除してください。

![](https://www.evernote.com/l/AAnRRA3XGt5LV6apH8yNmyBGRhajhMb3GlwB/image.png)
