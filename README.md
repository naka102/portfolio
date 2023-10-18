■ サービス概要

路線名 → 駅名を選ぶとその駅に関する情報を自由に投稿・閲覧できる SNS です。

ユーザーが写真や文字などで、選択した駅の綺麗な景色や美味しい飲食店に関する情報を

発信したり、他のユーザーの投稿を見ることができます。

■ このサービスへの思い・作りたい理由

快速が通過する小さな駅に行った時に、駅の規模からは想像できないような大きさのショッピングモールがあったり、豊かな自然があったりしたため、知らない駅の魅力を知る楽しさを実感したからです。

反対に、新宿や渋谷駅のような大きな駅でも意外と知らないような穴場スポットもあり、そのような自分だけが知っている小さな発見を多くの人に共有できたら楽しいと思いました。

■ サービスの利用イメージ

- 他ユーザーの投稿内容の閲覧
  1.路線一覧か路線名を選択(路線一覧上部にある駅名検索を使用すると３に飛ぶ)
  2.駅一覧から駅名を選択
  3.記事一覧に入るため気になる記事を選択
  4.記事詳細が表示
  5.投稿された記事の場所へ行く
- 記事の新規投稿(未登録ユーザーの場合 登録済ユーザーの場合は 3 から)
  1.路線一覧(画面トップ)のユーザー登録を選択
  2.ユーザー登録画面に入り、ユーザー ID・パスワード（必須）、マイ駅・お気に入りカテゴリ(任意)を入力し、登録
  3.路線名、駅名を選択
  4.記事一覧に入り、記事作成を選択
  5.記事登録画面に入り、タイトル・内容を入力、カテゴリを選択し、登録
  6.記事一覧に追加される
  駅一覧の仕様
  駅一覧では駅名の付近に、投稿された記事の数と一番多く登録のあったカテゴリを記載
  例）横浜駅　記事数:30 カテゴリ:和食

  カテゴリ機能
  ユーザーが興味のあるカテゴリを登録し、登録したカテゴリの多い駅を検索できる機能
  1.ユーザー登録時に関心のあるカテゴリを登録
  2.路線一覧でカテゴリ検索を選択
  3.ユーザーの登録したカテゴリの多い駅を一覧で表示
  例)ユーザーが和食をカテゴリ登録していた場合のカテゴリ検索結果
  横浜駅　記事数:30 カテゴリ:和食
  川崎駅　記事数:20 カテゴリ:和食
  マイ駅
  自分がよく利用する駅をマイ駅として登録しておき、マイ駅に近い駅(基本的には所属路線を対象)の投稿内容をビュー数の降順でピックアップする機能
  1.ユーザー登録時にマイ駅を登録
  2.トップ画面でマイ駅に近い駅の記事が自動的に紹介される
  (マイ駅は他のユーザに公開されない)

■ 機能候補

現状作ろうと思っている機能、案段階の機能をしっかりと固まっていなくても構わないので MVP リリース時に作っていたいもの、本リリースまでに作っていたいものをそれぞれ分けて教えてください。

MVP

未ログインユーザー

・トップ画面

・路線一覧

・駅一覧

・記事一覧

・記事詳細

・ログイン

・ユーザ登録

ログインユーザー

・マイページ

・高度機能　マルチ検索・オートコンプリート

→ 路線一覧に検索機能を実装予定

・お気に入り機能

本リリース

トップ画面

・マイ駅記事紹介

ユーザ登録

・カテゴリ登録

マイページ

・マイ駅登録

■ 機能の実装方針予定

フロントエンド

JavaScript

バックエンド

Rails 7.0 系

ユーザー登録認証

sorcery

DB

PostgreSQL

インフラ

Heroku

マルチ検索・オートコンプリート

Turbolinks

Stimulus

駅・路線情報

路線図は下記サイトの駅一覧と路線一覧の CSV をダウンロードできたため

こちらを DB にインポートする予定

https://ekidata.jp/
