# portfolio

■ サービス概要
本アプリは鉄道を日常利用していてもあまり詳しくない人に向けて
首都圏の複雑な路線網で誤乗車を防ぐ方法など鉄道の便利な知識を学べるクイズ・情報アプリです。

■ このサービスへの思い・作りたい理由
首都圏の複雑な路線網で発生しがちな誤乗車を減らしたいからです。

というのも、首都圏では電車の数が多く、1 つの駅でも多数の路線が乗り入れており、
その中には上野東京ラインや湘南新宿ラインなど行き先の異なる似た名前の路線が混乱を招いているからです。

これを間違えてしまうと、例えば下記のようなトラブルが起こるかもしれません。
「さいたま新都心」駅は上野東京ラインのみ停車するため、誤って湘南新宿ラインに乗車すると通過
もちろんこのようなトラブルはルート検索アプリを使用すれば防ぐことが可能ですが、それはルートの検索結果を厳密に守った場合の話です。
検索結果には「上野東京ラインに乗車してください」と記載していても、目の前に湘南新宿ラインがあれば、似たような名前のため、詳しくない人であれば、これに乗っても目的地に乗車できるだろうと考えても不思議ではありません。
そのため、ルート検索アプリがあったとしても鉄道の基礎的な知識を習得する必要は十分にあるといえます。

ところが、ネットでこれらの違いを調べてみてもマニア特有の長文に圧倒されることがあります。
これを受けてブラウザバックする人も跡を絶たないと知りました。
そのような理由から、鉄道に詳しくない人にも分かりやすい短文で解説し、少しでも楽しめるようにクイズ形式を導入することで日常の鉄道利用を便利にしたいと思い、本アプリの開発を考えました。

■ ユーザー層について
鉄道を日常利用していてもあまり詳しくない人
例:通勤・通学定期券で使用する範囲外で鉄道に乗る機会が少ない人（休日に電車移動をしない人）
地方から上京してきた人
（もしかしたらインバウンド需要もあるかも？）

■ サービスの利用イメージ
出発地と目的地を入力してその路線で少しでも早く移動するためのポイントや、誤乗車を防ぐ注意点などをクイズを通じて解説します。
クイズに答える余裕のない急いでいる人向けに「快速モード」として、クイズに答えなくても解説を検索、一覧表示することもできます。

■ サービスの差別化ポイント・推しポイント
よくある鉄道マニア向けの教養や専門的なクイズではなく、鉄道に詳しくない一般の方の日常的な鉄道利用をより便利にするための知識を獲得するクイズという点からターゲット層が異なっています。
そのため「〇〇系がー、パンタグラフが ▲□ などといったマニアックな知識は全て取り除いています。
あくまで実践的で日々の鉄道利用を役立てるものを選定するため、アプリの使用に対するハードルを下げています。

■ 機能候補
現状作ろうと思っている機能、案段階の機能をしっかりと固まっていなくても構わないので MVP リリース時に作っていたいもの、本リリースまでに作っていたいものをそれぞれ分けて教えてください。
MVP
・エリア一覧（まずは JR 東日本 首都圏編のみ）
・路線一覧
・クイズ一覧
・クイズ詳細
・解説見出し一覧
・解説詳細
・クイズ検索
・解説検索
・出発地と目的地を入力して関連する駅名や路線のクイズが表示される機能

本リリース
・お気に入り機能
・質問版機能
・SNS 的な交流機能
・高度機能　マルチ検索・オートコンプリート
・首都圏　私鉄編

■ 機能の実装方針予定
路線図 API の使用を検討しています。
