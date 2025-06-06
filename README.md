# js-shopping-cart
shopping cart built with JavaScript &amp; jQuery

#JavaScript ショッピングカート
このプロジェクトは、JavaScript と jQuery を使用したシンプルなショッピングカート機能のデモです。数量選択・カート追加・削除・合計金額の計算までをブラウザ上で動作確認できます。

#デモページ（https://rei-shi549.github.io/js-shopping-cart/）
実際のデモはこちら

#使用技術
HTML / CSS（簡易スタイル付き）
JavaScript（jQuery / jQuery UI）
DOM操作によるカート管理
アニメーション効果（バウンス、削除時のパフ）

#機能概要
商品一覧から数量を指定して「カートに追加」
同一商品は合算してカウント
カート内商品の「remove Cart」で削除可能
合計金額がリアルタイムに更新

⚠ 注意点（GitHub Pages用構成）
GitHub Pages上での動作を前提にしており、HTML内で <base href="/js-shopping-cart/"> を使用しています。
ローカル環境で動作させる場合は、パスの修正が必要になる場合があります。

#ファイル構成
bash
コピーする
編集する
/js-shopping-cart/
├── index.html
├── jQuery.js
├── apple.jpg
├── orange.jpg
├── grape.jpg

#制作意図・目的
JavaScriptとjQueryの基礎力を確認するための制作演習
Web制作実務における「ユーザーインターフェースと動的処理」の理解と実装練習

