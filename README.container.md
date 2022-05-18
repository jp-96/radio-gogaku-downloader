# VSCode + Docker

`VSCode` と `Docker` を使って、 `radio-gogaku-downloader.py` を実行できます。  


## インストール

次の２つをインストールします。

- [VSCode](https://code.visualstudio.com/download)
- [Docker](https://www.docker.com/get-started/)


## 準備

1. Docker を起動します。
1. VSCode で、このフォルダを開きます。
1. 拡張機能[Remote - Containers](ms-vscode-remote.remote-containers)をインストールします。


# radio-gogaku-downloaderの実行

## Containerの起動

1. VSCodeの左下に追加された `Open a Remote Window` をクリックします。
1. `Reopen in Container` を選択します。
1. `Container` が起動されるのを待ちます。  
※ 実行に必要なパッケージ等は、同時にインストールされます。


## 講座選択（-select）

1. メニューの `Terminal` から `Run Task...` を選択し、表示されたリストから `download - select` を選択します。
1. 講座選択画面が表示されますので、講座を選択し（マウスとスペースキー）、OKを押下します(マウスとEnterキー)。


## ダウンロード

1. メニューの `Terminal` から `Run Build Task...` を選択するとダウンロードが始まります。
1. ダウンロードされたファイルは、 `output` フォルダ内に保存されます。


# コマンド（Task）とオプション

`.vscode/tasks.json` ファイルで、 `radio-gogaku-downloader.py` を `Task` として実行できるように定義しています。  
コマンドとそのオプションに関しては、オリジナルの `README.md` を参照してください。  

