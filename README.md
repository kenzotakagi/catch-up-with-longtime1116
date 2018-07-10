# 技術書読書録
## 2018年
### 4月
- リファクタリング:Rubyエディション
rubyを書く上で常に手元に置いておきたい1冊。
自分がrubyから入った人間のせいか、beforeの部分でそんなことする？みたいなことも書いてあったが、逆にrubyじゃない言語に慣れている人の思考回路を学ぶいい機会になった。
大事なことはなぜbeforeがダメでafterがいいのか理由をしっかり言えること。
理由の言えないリファクタリングはただの知識であり、自分のプログラムへの応用に繋がらない。リファクタリングする際はこの本を思い出しつつ、理由づけも必ず行うようにする。
翻訳がわかりにくかったり、知らないプログラミング用語がでてきたりと理解が大変なところもあったが内容的にはかなり満足した。

### 5月
- Effective Ruby
リファクタリングrubyよりもtips的な書き方についての本だった。rubyに慣れてきた頃に読むといいと思った。
ruby(動的型付け言語)は初心者向けと思われがちだが、書く人の技術力次第でコードの質がかなり変わる言語。moduleの使い方が典型的だが、そのmoduleが継承階層にどう関わってくるのかなどの基本的な使い方は意外と知らないことがある。そのような言語理解について書かれていて、入門書の一つ上の本だと感じた。
さらっと読んでしまったのでもう一度読みたい。

### 6月

- 開眼!JavaScript
Reactわからん、ES6わからん、そもそもjsわからん、状態のそもそもを知るために読んだ。
他の言語から入ったプログラマにとってはとてもよい1冊。javascriptの言語的な特徴がとてもよくまとまっていた。rubyとの比較で考えると、関数、オブジェクト、prototype、constructor、クロージャあたりが特徴的であると感じた。newで生成したインスタンスとプリミティブ型で挙動が違ってきたりだとか、関数(function)がデータ型として扱われていたりだとか、rubyの方が書きやすいとは思いつつもこの使いにくい感がES6でどう改善されているか確かめる上で最適な本だったのではないか。

- WEB+DB PRESS vol87
Reactわからん、ES6わからん、そもそもjsわからん、状態の真ん中を知るために読んだ。
es5とes6の比較コードが常にあって非常に理解しやすい。
es6自体の感想は、rubyに似てきていて、とても便利になっている。が、似てきているからこそ言語の特性(0を真とするかしないかとか)を理解しないと気づかないうちにバグをうむコードを書きそうだということ。そういった意味で開眼jsを読んでからモダンjsを学んでよかったと思った。
非同期通信とかのチャプターは自分で実装しないと理解できないと思う。nodeとかをいじってみるのもありか。

- オブジェクト指向設計実践ガイド(サンディメッツ本)
読書会での題材。最高にわかりやすいオブジェクト指向の本。オブジェクトよりもメッセージに主眼を置き、どのようにして依存をなくすかが書かれている。どのようなコードが依存を生み、コードの変更を難しくしているかがとてもわかりやすい。全てのオブジェクト指向、動的型付け言語に当てはめることができる。インターフェースの書き方、抽象モジュールの導入、テストの書き方など、本当に勉強になった。静的型付けやgoなどの他の型付け言語をやってみてからもう一度やるとより理解が進むと思った。

