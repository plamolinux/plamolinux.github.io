---
layout: page
title: "Plamo 開発の歩み"
date: 2013-11-25 16:57
comments: false
sharing: false
footer: true
---

Plamo のリリースバージョン毎に時系列で，開発の歩み及び使用している kernel のバージョンを記録しています．

* [Plamo Linux 8.x シリーズ](#plamo8)
* [Plamo Linux 7.x シリーズ](#plamo7)
* [Plamo Linux 6.x シリーズ](#plamo6)
* [Plamo Linux 5.x シリーズ](#plamo5)
* [Plamo Linux 64 シリーズ](#plamo64)
* [Plamo Linux 4.x シリーズ](#plamo4)
* [Plamo Linux 3.x シリーズ](#plamo3)
* [Plamo Linux 2.x シリーズ](#plamo2)
* [Plamo Linux 1.x シリーズ](#plamo1)
* [Plagia 時代](#plagia)

### <a name="plamo8">Plamo Linux 8.x シリーズ</a>

* 2023-06-10 : Plamo 8.0 リリース

### <a name="plamo7">Plamo Linux 7.x シリーズ</a>

* 2018-05-19 : Plamo 7.0 beta1 リリース
* 2018-05-31 : Plamo 7.0 beta2 リリース
* 2018-06-13 : Plamo 7.0 リリース
* 2019-05-15 : Plamo 7.1 リリース
* 2020-05-13 : Plamo 7.2 リリース
* 2021-05-05 : Plamo 7.3 リリース
* 2022-04-30 : Plamo 7.4 リリース

### <a name="plamo6">Plamo Linux 6.x シリーズ</a>

* 2015-10-18 : Plamo 6.0 リリース
  * Plamo 6.0 の主な内容
    * kernel 4.2.3
    * Mate 1.10
    * Firefox 41.0/Thunderbird 38.3.0
    * MesaLib 10.6.7 + xorg-server 1.17.2
    * LibreOffice 5.0.2.2
    * get_pkginfo
    * UEFI/GPT 対応
    * UEFI インストール
* 2016-02-25 : Plamo 6.1 リリース
  * Plamo 6.1 の主な内容
    * UTF-8 対応
    * EFI システムパーティションの自動フォーマット
    * kernel 4.3.5
    * TeX Live 2015
    * ruby 2.2.3
    * llvm 3.7.0
    * 6.0 から 211 のパッケージ更新
* 2017-02-17 : Plamo 6.2 リリース
  * Plamo 6.1 以降に更新されたパッケージに追随するためのリリース

### <a name="plamo5">Plamo Linux 5.x シリーズ</a>

Plamo64-1.0 のパッケージを更新するとともに，32bit 環境をそれに合わせる形で構築し Plamo-5.x シリーズとしてリリース．

* 2012-12-15 : Plamo-5.0 beta 1 リリース
* 2012-12-24 : Plamo-5.0 beta 2 リリース
* 2012-12-29 : Plamo-5.0 リリース
  * Plamo-5.0 の主な内容
    * kernel 3.7.1
    * インストール時に btrfs が選択可能に
    * X11R77
    * glibc 2.16
    * grub 2.00/lilo 23.2
    * Xfce 4.10
    * KDE 4.9.2
    * GNU Emacs 24.2
* 2013-04-26 : Plamo-5.1 beta 1 リリース
* 2013-05-11 : Plamo-5.1 beta 2 リリース
* 2013-05-12 : Plamo-5.1 beta 3 リリース
* 2013-05-22 : Plamo-5.1 リリース
  * Plamo-5.1 の主な内容
    * kernel 3.9.3
    * MySQL -> MariaDB へ
    * KDE 4.9.5
    * LibreOffice 4.0.2
* 2013-12-13 : Plamo-5.2 beta 1 リリース
* 2013-12-20 : Plamo-5.2 beta 2 リリース
* 2013-12-29 : Plamo 5.2 リリース
  * Plamo-5.2 の主な内容
* 2014-01-14 : P-Plamo 5.2 リリース
* 2014-12-23 : Plamo 5.3 beta 1 リリース
* 2014-12-31 : Plamo 5.3 リリース
  * Plamo-5.3 の主な内容
    * kernel 3.17.6
* 2015-01-23 : Plamo 5.3.1 beta 1 リリース
* 2015-02-01 : Plamo 5.3.1 リリース
  * Plamo-5.3.1 の主な内容
    * kernel 3.17.6
* 2015-05-31 : P-Plamo 5.3.1 リリース

### <a name="plamo64">Plamo Linux 64 シリーズ</a>

まずは 64bit 環境で Plamo64-1.0 としてリリースし，その後 32bit 環境を更新し Plamo-5.x へ．

* 2010-10 : CLFS ( Cross Linux From Scratch ) をベースに64ビット版開発環境構築
* 2010-11 : Plamo64用パッケージの作成に入る
* 2010-11-11 : kernel を追加 ( kernel-2.6.35.7_plamo64-x86_64-P1 )
* 2010-12-15 : Plamo64-0.1 なツリー作成
* 2011-01-07 : Plamo64-0.1 内輪向けにリリース
* 2011-01-08 : kernel-2.6.36.2 に更新
* 2011-01-22 : Plamo-4.7x と Plamo-64-0.1 のツリーをマージして Plamo-5.0 のツリーに
* 2011-06-20 : kernel-2.6.38.4 に更新
* 2011-08-14 : kernel-2.6.39.4_plamoSMP に更新
* 2011-11-15 : kernel-3.0.9_plamoSMP に更新
* 2011-11-16 : kernel-3.1.1_plamoSMP に更新
* 2011-11-18 : 64 bits版を kernel-3.0.9_plamo64 に更新
* 2011-11-29 : kernel-3.1.4_plamoSMP に更新
* 2011-11-30 : 64 bits版を kernel-3.1.4_plamo64 に更新
* 2011-12-17 : Plamo64-RC1 リリース
* 2011-12-26 : Plamo64-RC2 リリース
* 2011-12-31 : Plamo64-1.0 リリース ( 64 bits版のみ )

### <a name="plamo4">Plamo Linux 4.x シリーズ</a>

* 2004-01-16 : 開発バージョンタグを plamo-4.0-a1 に変更．( kernel 2.4.24 )
* 2004-04-07 : plamo 4.0-beta1 を ftp で公開．( kernel-2.4.25-i386-P1 )
* 2004-04-18 : バージョンを beta2 に更新 ．( kernel-2.4.25-noarch-P2 )
* 2004-05-10 : バージョンを beta3 に更新．( kernel-2.4.26-i586-P2 )
* 2004-06-09 : バージョンを RC1 に更新．（kernel-2.4.26-i586-P3）
* 2004-06-25 : Plamo Linux 4.0 release.
  * 4.0 の主な内容．
    * Linux kernel 2.4.26 + ALSA
    * glibc-2.3.2
    * gcc-3.3.2
    * XFree86-4.4.0
    * KDE-3.2.2
    * ネットワーク設定ツール Planet を採用
    * 8 + 3 のパッケージ名の制限を無くす
    * 複数の CD-ROM からのインストールに対応
* 2004-06-29 : Plamo 4.1 へ branch． （kernel-2.6.7-i586-P1）4.0x も同時進行で更新が続く
* 2004-08-04 : 4.0 に xfplamoconfig を追加
* 2004-08-10 : 4.0 を kernel-2.4.27 + alsa-driver-1.0.5a に更新
* 2004-09-10 : plamo-4.01 release．（kernel-2.4.27）
* 2005-01-25 : 4.01 を kernel-2.4.29 + alsa-driver-1.0.8 に更新
* 2005-03-31 : 4.0 系のバージョンタグを plamo-4.02 に更新
* 2005-04-01 : plamo-4.02 release．（kernel-2.4.29 unicon対応)
* 2005-05-08 : plamo-4.1 のツリーは廃版にして，plamo-4.2 のツリーを構築
* 2005-05-15 : 4.2 系のバージョンタグを plamo-4.2-a1 に変更．（kernel 2.6.11.9 + vd_unicon）
* 2005-06-06 : 4.02 を kernel-2.4.31 + alsa-1.0.9a に更新
* 2005-07-03 : plamo-4.2-a1 を kernel-2.6.12.2 + unicon に更新
* 2005-07-06 : plamo-4.2-a1 を XFree86 から Xorg-6.8.2 に変更
* 2005-08-16 : 4.0 系の plamo-4.03 を release.（kernel-2.4.31）
* 2005-08-18 : 4.2-a1 を kernel-2.6.12.5 + unicon に更新
* 2005-09-07 : 4.2-a1 を kernel-2.6.13_SMP に更新
* 2005-11-12 : 4.2-a1 を kernel-2.6.14.2 に更新
* 2005-12-16 : 4.2-a1 を kernel-2.6.14.4 + unicon に更新
* 2006-01-07 : 4.2-a1 を kernel-2.6.15 に更新
* 2006-01-21 : 4.2-a1 を kernel-2.6.15.1 に更新
* 2006-02-03 : 4.2-a1 を kernel-2.6.15.2 に更新
* 2006-02-15 : 4.2-a1 を kernel-2.6.15.4 に更新
* 2006-03-09 : 4.2-a1 を kernel-2.6.15.6 に更新
* 2006-03-16 : 4.2 系を β2 として公開
* 2006-03-27 : 4.2 系のバージョンタグを β3 に更新
* 2006-03-29 : 4.2 β3 の kernel を 2.6.15.7 に更新
* 2006-04-01 : plamo-4.2 をリリース
* 2006-07-29 : 4.2 の kernel を 2.6.17.7 に更新
* 2006-08-18 : 4.xx 系のバージョンタグを 4.21 β1 に更新
* 2006-08-27 : 4.21 β1 の kernel を 2.6.17.11 に更新
* 2006-09-12 : バージョンタグをβ2に更新，kernel を 2.6.17.13 に更新
* 2006-10-05 : plamo-4.21 をリリース．
* 2007-06-20 : バージョンタグを plamo-4.22β1 に更新．( kernel-2.6.21.5_plamoUP-i586 )
* 2007-07-16 : 4.22β1 の kernel を 2.6.21.6 に更新．
* 2007-08-18 : 4.22β1 の kernel を 2.6.21.7 に更新．
* 2007-08-25 : バージョンタグを plamo-4.22β2 に更新．( kernel-2.6.21.7_plamoUP-i586 )
* 2007-09-06 : 4.22β2 の kernel を 2.6.22.6 に更新．
* 2007-09-11 : バージョンタグを plamo-4.22β3 に更新．( kernel-2.6.22.6_plamoUP-i586 )
* 2007-09-24 : バージョンタグを plamo-4.22RC1 に更新． kernel を 2.6.22.7-SMP に更新．( kernel-2.6.22.7_plamoSMP-i586 )
* 2007-09-27 : 4.22 RC1 の kernel を 2.6.22.9-SMP 版に更新．( kernel-2.6.22.9_plamoSMP-i586 )
* 2007-10-02 : バージョンタグを plamo-4.22 に更新．
* 2007-10-03 : plamo-4.22 をリリース．
* 2008-01-21 : Plamo-4.5 へのブランチ作業開始．kernel-2.6.23.14 に更新．
* 2008-01-23 : バージョンタグを Plamo-4.5a1 に更新．
* 2008-02-14 : kernel-2.6.23.16 に更新．
* 2008-05-05 : kernel-2.6.24.6 に更新．
* 2008-08-01 : kernel-2.6.26 に更新．
* 2008-08-02 : kernel-2.6.26.1 に更新．
* 2008-08-24 : バージョンタグを Plamo-4.5β1 に更新．
* 2008-09-07 : バージョンタグを Plamo-4.5β2 に更新．
* 2008-09-19 : kernel-2.6.25.17 に変更．
* 2008-09-23 : バージョンタグを Plamo-4.5β3 に更新．
* 2008-10-04 : Plamo-4.5rc1 リリース．
* 2008-10-12 : バージョンタグを Plamo-4.5 に更新．
* 2008-10-16 : Plamo-4.5 リリース． (plamo-4.51 に向けた開発続行．)
* 2009-01-15 : kernel-2.6.27.10 に更新．
* 2009-01-22 : バージョンタグを Plamo-4.51β3 に更新．
* 2009-02-03 : バージョンタグを Plamo-4.51 に更新．
* 2009-02-04 : Plamo-4.51rc1 リリース．
* 2009-02-11 : kernel-2.6.27.15 に更新．
* 2009-02-17 : バージョンを急遽 4.6β1 に更新．バージョンタグをPlamo-4.6β1 に変更
* 2009-02-25 : Plamo-4.6 リリース．
* 2009-06-23 : kernel-2.6.30 に更新．
* 2009-08-12 : kernel-2.6.30.4 に更新．
* 2009-08-17 : kernel-2.6.30.5 に更新．
* 2009-09-09 : Plamo-4.7β3 リリース．
* 2009-09-16 : kernel-2.6.30.7 に更新．
* 2009-09-23 : Plamo-4.7β4 リリース．
* 2009-09-30 : Plamo-4.7 リリース．
* 2009-11-04 : kernel-2.6.31.5 に更新．
* 2009-11-12 : kernel-2.6.31.6 に更新．
* 2009-11-16 : Plamo-4.71rc1 リリース．
* 2009-11-23 : Plamo-4.71 リリース．
* 2010-01-21 : kernel-2.6.31.12 に更新．
* 2010-02-20 : バージョンタグを Plamo-4.72rc1 に更新．kernel-2.6.32.9
* 2010-02-22 : Plamo-4.72rc1 リリース．
* 2010-03-01 : バージョンタグを Plamo-4.72 に更新．
* 2010-03-04 : Plamo-4.72 リリース．
* 2010-08-04 : kernel-2.6.32.16 に更新．
* 2010-08-10 : Plamo-4.73β1 リリース．
* 2010-08-20 : バージョンタグを Plamo-4.73 に更新．
* 2010-08-21 : Plamo-4.73β2 リリース．
* 2010-09-02 : Plamo-4.73 リリース． 以後 64 bits 版も含めた Plamo-5.0 の開発に入る．
* 2011-01-06 : kernel-2.6.36.2 に更新．
* 2011-05-04 : kernel-2.6.37.4 そして kernel-2.6.38.4 に更新．

### <a name="plamo3">Plamo Linux 3.x シリーズ</a>

* 2002/03/24 : 開発は Plamo 3.0 へ branch．
* 2002/03/26 : Plamo Linux 3.0-alpha1 ( kernel 2.4.18 ) に更新．
* 2002/05/30 : Plamo Linux 3.0-alpha1 を ftp で公開.
* 2002/08/05 : Plamo Linux 3.0-beta1 ( kernel 2.4.19 ) を ftp で公開.
* 2002/09/02 : Plamo Linux 3.0-beta2 に更新.
* 2002/09/18 : バージョン番号を Plamo-3.0 に更新．
* 2002/09/23 : Plamo Linux 3.0 release.
  * 3.0 の主な内容．
    * Linux kernel 2.4.19
    * glibc-2.2.5
    * gcc-2.95.3
    * XFree86-4.2.0
    * Perl-5.6.1
    * KDE-3.0.3
    * emacs-21.2
    * uClibc + BusyBox ベースのインストーラに移行
    * 2002/09/24 : Plamo Linux 3.1 の開発開始． ftp のツリーに Plamo 3.1 追加．
* Software Design 誌 2002 年 11 月号付録 CDーROM に 3.0 収録．
* 日経Linux 誌 '03 年 3 月号付録 CDーROM に 3.0 収録．
* Linux magazine 誌 2003 年 3 月号付録 CDーROM に 3.0 収録．
* Linux World 誌 2003 年 6 月号付録 DVD に 3.0 収録．
* 2003/04/18 : バージョン番号を Plamo-3.1 RC1 に更新．
* 2003/04/21 : ftp 版を Plamo Linux 3.1 RC1 としてまとめる．( kernel 2.4.20 )
* 2003/05/18 : Plamo Linux 3.1 release.
* 2003/05/20 : 3.2 の開発に移行．
* 2003/06/15 : バージョン番号を Plamo-3.2 に更新．
* 2003/06/17 : Plamo Linux 3.2 release．
* 2003/07/03 : Plamo-current は 3.3 ? の開発に移行．
* 2003/07/08 : 日経Linux 誌 2003 年 8 月号付録 CDーROM に 3.2 収録．
* 2003/08/20 : current version を 3.2.1 に更新．
* 2003/09/04 : kernel 2.4.22 採用に伴い version を 3.3に更新．
* 2003/09/15 : Plamo Linux 3.3 ftp release.
* 2003/09/29 : DOS/V POWER REPORT 誌 2003 年 11 月号付録 DVD に 3.3 収録．
* 2003/10/07 : Linux magazine 誌 2003 年 11 月号付録 CD-ROM に 3.3 収録．
* Plamo Linux 4.0 に向けた開発に入る．

### <a name="plamo2">Plamo Linux 2.x シリーズ</a>

* 1999-09-19 : Plamo Linux 2.0 α ( kernel 2.2.12 ) release.
* 1999-10-13 : Plamo Linux 2.0 α1 ( kernel 2.2.13 ) release.
* 1999-11-29 : Plamo Linux 2.0 β1 に更新．
* 2000-04-22 : Plamo Linux 2.0 release.
  * 2.0 の主な内容．
    * Linux kernel 2.2.14
    * glibc-2.1.2
    * gcc-2.9.5
    * XFree86-3.3.6
    * pcmcia-cs 3.1.3
    * emacs 20.6
* Linux Japan 誌 2000 年 7 月号付録 CD-ROM に 2.0 収録．
* Linux Magazine 誌 2000 年 8 月号付録 CD-ROM に 2.0 収録．
* 2000-09-29 : Plamo Linux 2.1 ( kernel 2.2.16 ) release.
* Software Design 誌 2000 年 11 月号付録 CD-ROM に 2.1 収録．
* 2001-04-13 : バージョン番号を Plamo-2.2 に更新． (kernel 2.2.19)
* 2001-05-05 : Plamo Linux 2.2 β4 に更新．
* 2001-05-21 : Plamo Linux 2.2 release.
* 2001-06-06 : Plamo Linux 2.2.1 release.
* 2001-06-28 : 技術評論社発行「PostgreSQL 完全攻略ガイド」 改訂第3版第1刷に 2.2 CD-ROM 収録．
* 2001-07-25 : 技術評論社発行「PostgreSQL 完全攻略ガイド」 改訂第3版第2刷に 2.2.1 CD-ROM 収録．
* 2002-03-23 : 2.2 系は Plamo 2.2.5 で Bug fix 以外開発終了．
* 2002-05-30 : こっそりと Plamo 2.2.6 ftp release．

### <a name="plamo1">Plamo Linux 1.x シリーズ</a>

* 1998-06-11 : pre-release CD-ROM を作成.
* 1998-06-20 : Plamo Linux 1.0 公開.
  * 記念すべきバージョンの主な内容．
    * Linux kernel 2.0.33
    * gcc-2.7.2.3
    * PJE 0.2b に追従
    * Slackware 3.4 & 3.5β に追従
    * XFree86-3.3.2
    * libc 5.4.44
* 1998-08-04 : Plamo Linux 1.1-pre release.
* 1998-08-15 : Plamo Linux 1.1 official release.
* 1998-08-23 : Plamo Linux 1.1.1 release.
* 1998-09-18 : Plamo Linux 1.1.2 第一回 Linux Seminar で配布.
* 1998-09-27 : Plamo Linux 1.1.2 release.
* 1998-10-05 : Plamo Linux 1.2 ( kernel 2.0.35 ) pre-release.
* 1998-10-18 : Plamo Linux 1.3 release.
* 1998-11-26 株式会社トッパン発行「Linux ネットワーク」 初版第1刷に 1.2 CD-ROM 収録．
* Software Design 誌 1998 年 12 月号付録 CD-ROM に 1.3 収録．
* 1999-01-23 : Plamo Linux 1.4pr5 ( kernel 2.0.36 ) release.
* 1999-02-16 : Plamo Linux 1.4.1 release.
* 1999-03-10 株式会社トッパン発行 「Linux インストールキット 第2版」に 1.4.1 CD-ROM 収録．
* Software Design 誌 1999 年 7 月号付録 CD-ROM に 1.4.4 収録．
* Unix User 誌 1999 年 7 月号付録 CD-ROM に 1.4.4 収録．
* 日経WinPC 誌 1999 年 8 月号付録 CD-ROM に 1.4.4 収録．
* 1999-11 技術評論社発行「改訂版 PC UNIX ユーザのための PostgreSQL 完全攻略ガイド」に 1.4.5 CD-ROM 収録．

### <a name="plagia">Plagia 時代</a>

* 1997 夏 : インストーラの日本語化，PCMCIA 対応の作業開始
* 1997-11-05 : plagia-alpha4 1st print ( kernel 2.0.31 ) 配布．
* 1997-11-06 : plagia-alpha4 2nd print 作成．
* 1997-12-13 : plagia-β1 ( kernel 2.0.32 ) を jaist で公開．
* 1998-02-11 : plagia-β2 ( kernel 2.0.33 ) を公開．
* 1998-03-18 : plagia-β2.1 CD-ROM を作成．
* 1998-03-24 : plagia-β2.2 にアップ．
* 1998-04-14 : plagia-pre-β3 を ftp で公開．
* 1998-04-24 : plagia-β3 の配布開始．
* 1998-05-24 : __Plagia から Plamo に改名．__



