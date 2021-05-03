---
layout: post
title: "パッケージ更新のチェック"
date: 2015-01-10 14:31:45 +0900
comments: true
tags: ["Plamo 5.x 情報"]
---

Plamo Linux用更新パッケージチェック&ダウンロードツールです。

詳細は以下のリンク先を参照して下さい。

* [PlamoWikiのこじまさんの日記](http://plamo.linet.gr.jp/wiki/index.php?diary%2FKojima%2F2015-01-06)

* [メーリングリスト](http://www.linet.gr.jp/~kojima/Plamo/ML/htdocs/201501/msg00003.html)

注意点をメーリングリストへの投稿から抜粋しておきます。

    updatepkg では更新できない(すべきでない)パッケージはチェック対象外にし
    ていますが，-b オプションを指定するとそれらの情報も表示します．ただし，
    これらのパッケージを単純に updatepkg で更新しようとすると，既存の設定ファ
    イルを上書きしたり，installpkg/updatepkg が動かなくなったりするので，
    十分ご注意ください．
    
    なお，このスクリプトはPlamo-5.2でも動くものの，5.2から5.3へはパッケージ
    の追加や廃止を伴なう大規模な更新になっているため，このスクリプトだけで
    は実用的ではありません．そのため動作環境は「Plamo-5.3以降」とさせてくだ
    さい．
