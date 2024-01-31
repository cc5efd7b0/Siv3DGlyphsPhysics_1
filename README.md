# Sban_Physics1  
## これ何？  
全てあなたの所為です。氏の「..」の映像にあるような物理演算をOpenSiv3Dで再現するやつです。  

## 使い方  
### Build Tools for Visual Studio 2022のインストール  
まず以下のリンクからBuild Tools for Visual Studio 2022をダウンロードします。  
https://visualstudio.microsoft.com/ja/downloads/#build-tools-for-visual-studio-2022  
ダウンロードされたファイルを実行します。  
続行→C++によるデスクトップ開発にチェックを入れる→インストール  
分かりづらい場合は[こちら](https://www.kkaneko.jp/tools/win/buildtool2022.html)などが参考になると思います。  
  
### OpenSiv3DのSDKのインストール  
次に、[こちら](https://siv3d.github.io/ja-jp/)からSDKをダウンロード、実行します。  
詳細はリンク先に記載されていますので、そちらに従ってください。  
ここで再起動をしておいたほうがいいかもしれません。  

### ソースコードのダウンロード、配置  
次に、[こちら](https://github.com/0x-sinsu/Sban_Physics1)のページの「Code」をクリック、「Download ZIP」をクリックしてダウンロードします。  
(gitでも問題なし)  
任意のフォルダに配置します。  
Physics1.slnがあるフォルダのパスを控えておきます。  
次に、Main.cppをVSCodeなどで開きます。
編集する箇所をコメントアウトで示していますので、それを参考に編集してください。  
分からない所があればTwitterのDMやDiscordまでどうぞ。  
Twitter:[@0x_sinsu](https://twitter.com/0x_sinsu)  
Discord:subete_light  
  
### ビルド
次にスタートメニューで「x64 Native Tools Command Prompt for VS 2022」と検索し、出てきたものを実行します。  
そこに以下のコマンドを貼り付け、実行します。  
```Batchfile
msbuild "先ほど控えたフォルダパス\Physics1.sln" /p:Configuration=Release /p:Platform=x64
```
大量の文が流れてきますが、そのまま入力待機状態になるまで待ちます。  
ビルドが終了すると、Intermediate\Physics1\Release内にexeファイルが出来ています。  
### このプログラムはフルスクリーンで実行されます。  
### 「Esc」キーを押すことでプログラムは終了します。  
### また、5分が経過すると自動で終了するようにもなっています。  
実行される画面のサイズ変更方法などはいずれ追記します。変更するのであれば意図する動作になるようにご自由にコードを書き換えてください。  
