# 山形県新型コロナウィルス感染状況の視覚化


## Overview

山形県の [新型コロナウィルス感染症に関連するポータルサイト](http://www.pref.yamagata.jp/ou/bosai/020072/kochibou/coronavirus/coronavirus.html) で公開されている確認事例をもとに感染者が増える様子を時間軸で視覚化してわかりやすくしたもの。

ページを開くと感染が確認された人が、その居住地のあった市区町村内※に表示されていきます（青は男性、赤は女性）。表示順は症例番号ごとですが、簡単にいうと **感染が確認された日** ごとに2秒おきに表示されていきます。また地図上に表示される紫の線は家族や同居、同じ職場での勤務など、他事例との濃厚接触が疑われる関係があったと記録されている関係を示しています。

※**地図上に表示される症例者の位置は居住地や勤務地などとは関係ありません。あくまで公開されている市区町村レベルでの大まかな位置を表示しています。** 例えば山形市で感染者が報告された場合は山形市役所の周辺に集まって表示されるようになっています。


## References

ここで公開されている情報を元に独自データ化しています：

http://www.pref.yamagata.jp/ou/bosai/020072/kochibou/coronavirus/coronavirus.html


## Licensing

This code is licensed under MIT.


## Copyright

2020 [K.Kimura @ Juge.Me](https://github.com/dotnsf) all rights reserved.
