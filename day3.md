# 2016/05/09

## 本日のゴール

* Excel/CSVを取り込んでアプリを作ってみる
* JavaScriptを使うとkintoneがもっと使いやすくなることに気付く

## 本日の課題

### Excel/CSVを取り込んでアプリを作ってみよう

普段はアプリを作成する時「はじめから作成」で作りますが、今回は「Excel/CSVから作成」を選んで既存のデータを取り込んでみましょう

今回講義用に[沖縄県専修学校各種学校協会](http://www.okisenkaku.or.jp/)の[加盟校一覧データ](data/okisenkaku.csv)を作りました。

このデータを取り込んでアプリを作ってみましょう。アプリを作る際に気を付けることは

* 文字コードを **UTF-8** にしてください。
* フィールドタイプが自動的に認識されますが、「地区」を「ドロップダウン」にしてください(っていうか勝手にここまで自動認識してくれるんだ…)

です。 

### はじめよう kintone JavaScript APIを触ってみる

[はじめよう kintone JavaScript API](https://cybozudev.zendesk.com/hc/ja/sections/200332780-%E3%81%AF%E3%81%98%E3%82%81%E3%82%88%E3%81%86-kintone-JavaScript-API)の第1回から第8回くらいまでをやってみましょう。

エディターがどうとかなんか動かないんだけど!!!とか思った学生は2〜3年生の先輩に聞いて解決してください。

**彼らはそういうの解決するの得意ですから大丈夫です!!!**

### サンプルを参考にいろいろカスタマイズしてみる

[Tips - cybozu.com developer network](https://cybozudev.zendesk.com/hc/ja/categories/200030560)のページにはいろいろサンプルの例が載っています。

業務で使うにあたって特に便利そうなのでいうと

* [郵便番号→住所について](https://cybozudev.zendesk.com/hc/ja/articles/203853280-%E9%83%B5%E4%BE%BF%E7%95%AA%E5%8F%B7-%E4%BD%8F%E6%89%80%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6)
* [Font Awesome を使ってメニューにかっこいいアイコンを配置する方法](https://cybozudev.zendesk.com/hc/ja/articles/208192343-Font-Awesome-%E3%82%92%E4%BD%BF%E3%81%A3%E3%81%A6%E3%83%A1%E3%83%8B%E3%83%A5%E3%83%BC%E3%81%AB%E3%81%8B%E3%81%A3%E3%81%93%E3%81%84%E3%81%84%E3%82%A2%E3%82%A4%E3%82%B3%E3%83%B3%E3%82%92%E9%85%8D%E7%BD%AE%E3%81%99%E3%82%8B%E6%96%B9%E6%B3%95)

あたりを覚えておくといろいろいい感じがしますのでこれらのサンプルを実行してみてください
