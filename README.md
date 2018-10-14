# graphviz edit reloader
.dotファイルを更新するとchromeで見ている.svgファイルを自動で更新する奴

# How to use
- chromeにlivereload extensionをインストール
https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei

- 以下のコマンドを実行
```
git clone <this repository>
cd graphviz_edit_reloader
bundle install
bundle exec guard -i
```

- index.htmlをchromeで開く
- chrome右上のlivereload extensionアイコンからlivereloadを有効にする
- 好きなエディタでsample.dotを編集する
