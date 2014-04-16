# 第2回デスマコロシアム 解答チェックツール

## 概要
第2回デスマコロシアムの問題の解答をideone上でチェックするツールです。  
Greasemonkeyのユーザースクリプトなので、ブラウザがGreasemonkeyに対応している必要があります。  

Windows7 + GoogleChromeおよびFireFoxの最新バージョンで動作確認済みです。  

## インストール方法
### GoogleChromeの場合
* 当ページの画面右側にある「Download ZIP」ボタンをクリックします。  
  ※gitになれている方はcloneしてもらった方が早いです

* ダウンロードしたZIPを解凍します。
* GoogleChromeを起動します。
* メニューからツール＝＞拡張機能を選択します。
* 拡張機能のタブがアクティブで表示されている状態で、先ほどダウンロードした「deathma2_answer_check.user.js」をドラッグ＆ドロップします。
* 以上で設定完了です

### FireFoxの場合
※あらかじめGreasemonkeyのアドオンをインストールしておきます

* 当ページの画面右側にある「Download ZIP」ボタンをクリックします。
* ダウンロードしたZIPを解凍します。
* FireFoxを起動します。
* Greasemonkeyのメニューからユーザースクリプトの管理を選択します。
* 管理のタブがアクティブで表示されている状態で、先ほどダウンロードした「deathma2_answer_check.user.js」をドラッグ＆ドロップします。
* 以上で設定完了です

## 利用方法
* ブラウザを起動します
* コンソールを表示します（ChromeならCtrl+Shift+J、 FireFoxならCtrl+Shift+K）
* ideoneで任意のコードを実行します
* 結果画面の表示が終わったら画面のどこかをクリックします
* コンソールに結果が表示されます。正しければ「OK」。間違ってれば「NG」と表示されます

※出力内容や出力形式を変えたければ、ダウンロードした「deathma2_answer_check.user.js」を変更してから  
ユーザースクリプトをインストールしてください。  
より使い易くしたツールを拡散して配布したければ当プロジェクトをフォークしてください。

## 補足
* Greasemonkeyを使ったことがない方に「こういうことができますよ」というサンプルをみていただく意味もあるので  
  興味を持っていただけたらGreaseonkeyの問題である「他人のサイトにモンキーパッチ問題」にも挑戦していただけると幸いです。  
  「他人のサイトにモンキーパッチ問題」  
  https://codeiq.jp/ace/tbpgr/q826  

* 少し改造して他のideoneを利用した問題用のツールにするのもいいかもしれませんね
