---
layout: post
title: "Plamo 5.3.1 リリース"
date: 2015-02-02 15:42:31 +0900
comments: false
tags: ["リリース情報", "Plamo 5.x 情報"]
---

Plamo Linux 5.3.1 をリリースしました。

* [リリースアナウンス](http://www.linet.gr.jp/~kojima/PlamoWeb/ML/htdocs/201502/msg00000.html)

gihyo.jp の連載「玩式草子─ソフトウェアとたわむれる日々」で Plamo 5.3.1 の詳細がまとめられています。

* [玩式草子─ソフトウェアとたわむれる日々　第66回　Plamo-5.3.1とget_pkginfoスクリプト](http://gihyo.jp/lifestyle/serial/01/ganshiki-soushi/0066)

メーリングリストへの投稿です。

    昨年末にリリースしたPlamo-5.3の改訂版となる，Plamo-5.3.1を1月末にリリー
    スしました．
    
    $ ls -lh plamo-5.3.1*
    -rw-r--r-- 1 kojima plamo 3.5G  1月 30 22:49 plamo-5.3.1_x86_64_dvd.iso
    -rw-r--r-- 1 kojima plamo   61  1月 30 22:49 plamo-5.3.1_x86_64_dvd.iso.md5sum
    -rw-r--r-- 1 kojima plamo 3.7G  1月 30 22:50 plamo-5.3.1_x86_dvd.iso
    -rw-r--r-- 1 kojima plamo   58  1月 30 22:50 plamo-5.3.1_x86_dvd.iso.md5sum
    
    すでに ring.yamanashi.ac.jp にはミラーいただいているものの，ringサーバ全
    体に届くにはもう少し時間がかかるようです．

    このリリースの詳細については，gihyo.jpのサイトで公開している連載記事に
    まとめているので，そちらでご確認くださいませ．

    http://gihyo.jp/lifestyle/serial/01/ganshiki-soushi/0066

    あわせて，Plamo-5.2から5.3.1への更新集(アップデータ)を，
    Update/5.2_5.3.1/ 以下に公開したので，Plamo-5.2をご利用の方はこちらを
    ご利用ください．
    
    $ ls -F Update/5.2_5.3.1/
    README.kernel_update  README.update  x86/  x86_64/
    
    $ ls -F Update/5.2_5.3.1/x86_64/$ ls -F Update/5.2_5.3.1/x86_64/
    00_base/  01_minimum/  02_x11/  03_xclassics/  04_xapps/  05_ext/
    ...
    
    $ ls -F Update/5.2_5.3.1/x86_64/00_base/
    bash-4.2.53-x86_64-P1.txz        libgcc-4.8.4-x86_64-P1.txz           openssl-1.0.1k-x86_64-P1.txz
    coreutils-8.23-x86_64-P2.txz     linux_firmware-201501-noarch-P1.txz  shadow-git_20130908-x86_64-P3.txz
    dhcp-4.2.7-x86_64-P1.txz         linux_pam-1.1.8-x86_64-P1.txz        sudo-1.8.11p2-x86_64-P1.txz
    file-5.22-x86_64-P1.txz          lsb_release-1.4-noarch-P3.txz        update.sh*
    ...
    
    アップデータは，従来同様，00_baseから11_mateのカテゴリごとに分け，各ディ
    レクトリには更新用の update.sh を置いてますので，ディレクトリごとダウ
    ンロードして，そのディレクトリの update.sh を実行すれば更新できるはずです
    (が，あまり細かくテストしてないので何かあったらごめんなさい ;-)
    
    # カーネルは update.sh では更新しないので，README.kernel_update を参考
    # に手動で更新してください．
    
    Plamo-5.3 からは，get_pkginfo.py というスクリプトを使って更新されたパッ
    ケージを簡単にダウンロードできるのでアップデータとしては提供していません．
    
    get_pkginfo.py は https://github.com/plamolinux/get_pkginfo から入手でき，
    上記 gihyo.jp の記事でも簡単に触れているのでご参照ください．
    
    バグやトラブルレポート，各種要望等は，従来同様，plamo.linet.gr.jp の
    wiki ページやこの ML へお気軽に連絡ください．
    
    それでは，今後とも Plamo Linux をよろしくお願いします．