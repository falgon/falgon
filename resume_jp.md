# Resume ![badge](https://img.shields.io/badge/Last%20updated-2023%2F04%2F12-brightgreen.svg)

<img src="https://avatars.githubusercontent.com/u/1241783?s=400&u=dee28487989ded5b417672468b4b942d00abde1b" width="200" alt="profile image" align="left" />
<ul style="display: list-item; list-style: none;">
    <li>ハンドルネーム: Roki</li>
    <li>ウェブサイト: <a href="https://roki.dev">roki.dev</a></li>
    <li>ブログ: <a href="https://roki.dev/roki.log">roki.dev/roki.log</a></li>
    <li>Zenn: <a href="https://zenn.dev/roki">zenn.dev/roki</a></li>
    <li>Note: <a href="https://note.com/_roki/">note.com/_roki/</a></li>
</ul>

<br clear="left">

## 略歴

| 年 | 内容 |
| :--: | :--: |
| 2020 | [デジタルハリウッド大学](https://www.dhw.ac.jp/)デジタルコミュニケーション学部デジタルコンテンツ学科卒業 |
| 2020〜 | [KLab株式会社](https://www.klab.com/jp/)入社・KLabGames事業本部サーバ運用エンジニアとして従属 |

## お仕事内容

2020 年より KLab 株式会社 KLabGames 事業本部へ配属。某有名 IP ゲームの Python3 + Flask によるサーバ新規開発/機能改善を経験。その後、同案件サーバ運用チームへ。施策展開/保守メンテナンス、サブリーダー担当、デプロイシステム改善/構築やパイプライン化、年に一度開催される世界大会の開発運用メイン担当等従事。
その他、これがあったら便利そうというツールを自作し社内で活用したり、それらの経験から得た知識を基に QA に回答、社内メールに技術情報を発信したり、新入社員のチューター、Git 等の基本的な使い方を教授するバージョン管理研修の講師や、基本的な RDB や KVS の概念から使い方を教授するデータベース演習の講師を務めたりしている。

業務上で用いている技術のキーワード: Python, MySQL, Jenkins, Nginx, Bash, AWS athena, Debian Linux, ...

## 好きな技術

### 車輪の再発明

<i>車輪の再発明</i>がすき。
これまでの主な<i>車輪の再発明</i>リスト：
- [Cコンパイラ - htcc](https://github.com/falgon/htcc)
    - 関連記事: [Haskell で C コンパイラを作ってみた](https://roki.dev/roki.log/2020/03/17/SelfMadeCCompiler/index.html)
- [Git - hmgit](https://github.com/falgon/hmgit)
    - 関連記事:
        1. [技術書展 11 にて Git (一部) を自作する記事を執筆した](https://roki.dev/roki.log/2021/07/10/SelfMadeTinyGit/index.html)
        2. [技術書典11で同人誌を頒布します & 既刊PDFダウンロードページ](https://www.klab.com/jp/blog/tech/2021/tbf11.html)
- [JPEGエンコーダ/デコーダ - jpezy](https://github.com/falgon/jpezy)
    - 関連記事:
        1. [カラー画像の原理からJPEGの圧縮原理までの学習メモ](https://roki.hateblo.jp/entry/2017/04/10/JPEG%E3%81%AB%E3%81%A4%E3%81%84%E3%81%A6%E5%AD%A6%E7%BF%92%E3%83%A1%E3%83%A2)
        2. [JPEG エンコーダ書いた](https://roki.hateblo.jp/entry/2017/07/02/JPEG_%E3%82%A8%E3%83%B3%E3%82%B3%E3%83%BC%E3%83%80%E6%9B%B8%E3%81%84%E3%81%9F)
        3. [JPEG デコーダ書いた](https://roki.hateblo.jp/entry/2017/08/13/JPEG_%E3%83%87%E3%82%B3%E3%83%BC%E3%83%80%E6%9B%B8%E3%81%84%E3%81%9F)
        4. [non-type template parameter におけるデータの受け渡しから TMP で実数を含む value computing を行う](https://roki.hateblo.jp/entry/2017/09/01/non-type_template_parameter_%E3%81%AB%E3%81%8A%E3%81%91%E3%82%8B%E3%83%87%E3%83%BC%E3%82%BF%E3%81%AE%E5%8F%97%E3%81%91%E6%B8%A1%E3%81%97%E3%81%8B%E3%82%89_TMP_%E3%81%A7%E5%AE%9F%E6%95%B0%E3%82%92%E5%90%AB)
- [ping - network-basal](https://github.com/falgon/network-basal)
    - 関連記事: [Haskell でリンクレイヤーにおける ICMP パケットの構築, 送受信および解析による ping の実装](https://roki.dev/roki.log/2018/09/15/scratchPacket/index.html)

### 関数プログラミング

関数プログラミングがすき。一番好きな言語はHaskell。
C++テンプレートを純粋関数型言語だと思っており，一例としてはその機構を使ってコンパイル時 Lazy K インタプリタを作ったりした。
- [コンパイル時 Lazy K インタプリタ - mpl-lazyk](https://github.com/falgon/mpl-lazyk)
    - 関連記事:
        1. [C++ テンプレートメタプログラミングによるコンパイル時 Lazy K インタプリタ](https://roki.dev/roki.log/2020/12/16/CompileTimeLazyKWithCXXTemplateMetaProgramming/index.html)
        2. [発表動画](https://klab-fukuoka-meetup.connpass.com/event/199452/)
        3. [Reddit への掲載](https://www.reddit.com/r/cpp/comments/kt72dz/lazy_k_interpreter_in_c_template_metaprogramming/)

C++20まではC++言語仕様書の重箱の隅をつついたり，ドラフト仕様や提案を追っていたりした。

### その他

その他自分自身でよく使う自作の物々。

- [Hakyll 製 ポータルサイト - roki-web](https://github.com/falgon/roki-web)
    - 私のポータルサイト https://roki.dev の実装。Hakyll という static site generator を使っている。その他色々妙にこだわりポイントがあるので下記記事を参照
    - 関連記事
        1. [個人ページ, ブログを移行した](https://roki.dev/roki.log/2020/08/25/hello-roki-web/index.html)
        2. [Hakyllで個人ウェブページを作りましたので全体概要を紹介](https://www.klab.com/jp/blog/tech/2020/0924-Hakyll.html)
- [自作 LINE ボット - line-bot-kiirotori](https://github.com/falgon/line-bot-kiirotori)
    - 私が日常生活を便利にするのにおいて個人的に使っている LINE BOT の Haskell 実装
    - 関連騎士: [簡易認証, 指定時間実行可能な LINE Bot の自作](https://roki.dev/roki.log/2022/04/10/LineBotDevelopment/index.html)

## 業務外での技術的活動

- OSS への貢献
    - [C++ 標準化委員会ペーパー内のサンプル実装への PR](https://github.com/PeterSommerlad/SC22WG21_Papers/pull/5), [C++ へマルチステージプログラミングを導入することを試行した Meta C++ コンパイラ実装への PR](https://github.com/meta-cpp/clang/pull/1), [restyler への dhall 言語対応 PR](https://github.com/restyled-io/restylers/pull/96) ... など他プロジェクトへのコントリビュートは <https://roki.dev> の Contributions を参照
- 書籍
    - [KLab Tech Book Vol.8, 第七章『ミニマル Git を自作しよう』](https://techbookfest.org/product/6185615265628160) - [技術書典 11](https://techbookfest.org/event/tbf11)
        - [関連記事1](https://roki.dev/roki.log/2021/07/10/SelfMadeTinyGit/index.html)
        - [関連記事2](https://www.klab.com/jp/blog/tech/2021/tbf11.html)
        - :star2: **[ミニマル Git を自作しよう！（加筆/調整/改定版）](https://note.com/_roki/)**
- 発表
    - C++ テンプレートメタプログラミングによるコンパイル時 Lazy K インタプリタ - [KLab Engineer Advent Calendar 2020 Recap Day1](https://klab-fukuoka-meetup.connpass.com/event/199452/)
        - [関連記事](https://roki.dev/roki.log/2020/12/16/CompileTimeLazyKWithCXXTemplateMetaProgramming/index.html)
        - [動画](https://www.youtube.com/watch?v=OTYsKSZNbZc&feature=emb_title&ab_channel=klab_tech)
