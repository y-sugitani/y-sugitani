# この文章について

この文章は杉谷の2022年4月現在のプロフィールと職務経歴書を合わせた物です。

## 基本情報

- 杉谷 保幸(スギタニ ヤスユキ) 
- 男性 / 40歳
- 神奈川県
- [SpeakerDeck](https://speakerdeck.com/sugitani) / [SlideShare](https://www.slideshare.net/yasuyukisugitani/presentations) / [ブログ](https://sugitani.hatenablog.com/) / [Zenn](https://zenn.dev/sugitani) / [Twitter](https://twitter.com/sugitani) ※技術の話はそれほどありません

## これまでの評判のあった発表資料や技術エントリ

- 2019 スタートアップがまともなわけ無いから入るな [前編](https://mynavi-agent.jp/it/geekroid/2019/08/sugar-1.html)・[後編](https://mynavi-agent.jp/it/geekroid/2019/08/sugar-2.html)
- 2019 [SUGARのアーキテクチャー / SUGAR ARCHITECTURE](https://speakerdeck.com/sugitani/sugar-architecture-20190425)
- 2017 [初転職4年間のまとめ、あるいはCTOを辞めたお話](https://sugitani.hatenablog.com/entry/2017/10/01/122714)
- 2016 [2015〜2016年で開発組織を作るためにやってみたこ2015〜2016年で開発組織を作るためにやってみたこと](https://labs.septeni.co.jp/entry/2016/08/22/152549)
- 2015 [Scalaに至るまでの物語 - Septeni × Scala 第一回 杉谷](https://www.slideshare.net/yasuyukisugitani/septeni-scala)
- 2016 [Scala/Scrum/DDD 困ったこと50連発ガトリングトーク！！](https://www.slideshare.net/yasuyukisugitani/scalascrumdddgatlingtalk)
- 2015 [GANMA!でDDDをやってみてから1年くらい経った](https://www.slideshare.net/yasuyukisugitani/septeni-scala3)
- 2015 [技術的負債について考えた](https://sugitani.hatenablog.com/entry/2015/05/23/205714)
- 2014 [2014年。開発組織を作るためにやってみた事](https://labs.septeni.co.jp/entry/20141231/1419955978) 



## 代表的な作ってきたプロダクト

- [SUGAR](https://apps.apple.com/jp/app/id1395793196)  - SUGAR社による芸能人と（本当に）話せるライブアプリ、佐藤健の配信で三〇万人以上の同接を記録
- [GANMA!](https://ganma.jp/) - セプテーニ子会社のコミックスマート社によるオリジナルコミック配信サイト/アプリ
- [ニコニコ生放送](https://live.nicovideo.jp/) - ドワンゴ社によるライブ配信サイト



## 経歴(簡易)

- 2021- 株式会社FORO(CTO) / SUGAR株式会社(技術顧問)
- 2017-2021 SUGAR株式会社(CTO)
- 2013-2017 株式会社セプテーニ・オリジナル(CTO) ※現:株式会社FLINTERS
- 2006-2013 株式会社ドワンゴ
- 2006 電気通信大学 情報工学科卒業

## 出来ること

Scala/TypeScript/JavaScript/Swift/Kotlinを現役で扱っています。


### ①単騎でシステム一つ、まるごと作れます。運用もできます

例えば「Clubhouseっぽいもの作って」と言われたらデザイナーさんだけ確保していただければ、おそらくすべて一人で作りきることができるくらいいろんな事ができます。※っぽいものを作ることをおすすめしているわけではありません



直近（SUGAR/GANMA!）での具体例

- ScalaによるREST APIサーバ実装
- SwiftによるiOSアプリの作成
  - 若干Metalも。
- KotlinによるAndroidアプリ
  - 若干OpenGL ESも
- インフラ構築・運用
  - SUGARではGCP(GKE -  Google Kubernetes Engineを主に利用)がメイン
  - GANMA!ではAWSがメイン



特記事項として動画配信・ライブ配信の経験が多く、出来ることが多いです

- WebRTCを利用したシステムを構築できます(具体的にはlibwebrtcとKurentoを利用した開発/Kurentoの改造・プラグイン作成(C++))
- HLS配信に関する様々なことができます（具体的にはWowzaを利用したシステム作成/Wowzaプラグイン開発/CDNを使っての大規模配信のインフラ構築）
- WebSocketによるリアルタイム通信やServer-sent Eventsによる大規模リアルタイムPUSHに慣れています



企画開発面においては、できればプロダクトオーナーに相当する専門の方がいらっしゃるのが理想ですが
確保できない場合は[MIRO](https://miro.com/)などを駆使してヒアリングや検討・議論を行い、できるだけ良い形にする努力を行えます。



### ②綺麗なコードを書くために努力しています

ニコニコ生放送で衛生を上手く維持することが出来ず、関係者の方々に辛い思いをさせてしまった経験から、よい道具（言語やツールやDDDなどの手法）を適切に扱い、良い状態を長く続けられるように努力することに注力をしています。



こちらに関する詳細は

Scalaに至るまでの物語 - https://www.slideshare.net/yasuyukisugitani/septeni-scala

や

技術的負債について考えた - https://sugitani.hatenablog.com/entry/2015/05/23/205714

をご参照ください。



### ③膨大な負荷やトラフィックに耐えられるシステムを作成できます

これまでのプロダクトは尋常ではないトラフィックに苦しめられたプロダクトが多く、特にSUGARでは通知により一瞬で三〇万人超が殺到するシステムでした。最初から一切落ちないシステムを作れるぜ！とまではいきませんが、トラフィック増を考慮したシステム設計と実装を行うことが出来ます。



またAkamaiやFastly、CloudfrontなどのCDNを活用した大規模トラフィックを扱うシステムを構築できるほか、各業者との価格交渉も行えます。



### ④開発組織を作った実績があります

前職（セプテーニ・オリジナル,現FLINTERS)でも現職でもCTOを務めています。 特に前職ではPHPがメインだった昔ながらの開発組織をScalaをつかい、手法を学び、スクラムなども活用するモダンな開発を行う組織に成長させることに成功しました。



具体的には

- 良い道具(Scalaやスクラム等)や良い概念(DDD等)をつかいましょう、という方針の整備とお膳立て
- 良い開発を行うための環境整備（テストを書きましょうレビューをしましょう、という基本的なところから外部アドバイザー導入などの手段も含めての"意識"を保てるようにする調整）
- 各種開発系イベントへのブース出展やイベント開催による採用強化

などを行うことが出来ます。



実施したことの詳細は以下のブログエントリをご参照ください

- 2014年。開発組織を作るためにやってみた事 -  https://labs.septeni.co.jp/entry/20141231/1419955978
- 2015〜2016年で開発組織を作るためにやってみたこと - https://labs.septeni.co.jp/entry/2016/08/22/152549 
- 初転職4年間のまとめ、あるいはCTOを辞めたお話 - https://sugitani.hatenablog.com/entry/2017/10/01/122714

