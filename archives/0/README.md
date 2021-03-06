第0回　Shimokita.js
====

## イベントリンク

[https://www.facebook.com/events/158189694341952/](https://www.facebook.com/events/158189694341952/)

## やったこと

### 今後のShimokita.jsについての話し合い

- 決まったこと
    - Shimokia.jsの[README](https://github.com/osscafe/shimokita.js)にまとめてます。


### 大規模JavaScript開発について (by [@tan_yuki](https://twitter.com/tan_yuki))

- [プレゼン資料](http://www.slideshare.net/yukitanakanarachan/java-script-17005163)
- 大規模になると大変なので最初からでかくなることを想定してコーディングしましょう
- Global変数は減らしましょう
    - 無名関数(function() { })()を使ってスコープ制限
    - プロジェクトに対してGlobal変数はひとつにする
    - 外出ししたいものはそのGlobal変数の子供として定義する
- オブジェクト指向っぽくコーディングしましょう
- テストの自動化を心がけましょう


## 話に出たツールなど

- [modern.IE](http://www.modern.ie/ja)
    - macでIEをテスト
- [Charles](http://www.charlesproxy.com/)
- [Grunt.js](http://gruntjs.com/)
    - nodejs製のビルドツール
- [enja-oss](https://github.com/enja-oss)
    - OSSのドキュメント・コメントを日本語訳するプロジェクト
- あと忘れました。。。。だれか追記して下さい。
    - chromeなんちゃらってのが思い出せん…  
- [CodeKit](http://incident57.com/codekit/)
- [Livereload](http://livereload.com/)
    - HTMLとかCSSを書いたら自動でブラウザリロードして同期してくれる
- [Fake](http://fakeapp.com/)
    - フロントエンドテスト自動化ツール
    - Seleniumの代わりになる？
