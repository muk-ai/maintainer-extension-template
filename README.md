# maintainer-extension-template
使い方
- `manifest.json`の`host_permissions`に拡張機能を動作させたいURLを追加する。
- `rules.json`の`condition.urlFilter`に拡張機能を動作させたいURLを設定する。
- `rules.json`の`action.requestHeaders`のheaderとvalueを任意の文字列に変更する。
- Chromeに拡張機能として追加する。
  - 拡張機能を管理 (chrome://extensions/) を開く
  - 右上のデベロッパーモード トグルをOnにする
  - 左上に現れた「パッケージ化されていない拡張機能を読み込む」でこのリポジトリをクローンしたディレクトリを選択する
