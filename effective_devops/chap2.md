# 第2章 devopsとは何か

> "devops"は文化運動だ。（p.13）
> "devopsは思考の方法であり、仕事の方法でもある" (p.13)


## 2.1 文化のための処方箋

- devopsはそれ自体が利益となるものではなく、物事を改善するための処方箋（改善策？）
- devopsは文化運動
  - 価値観
  - 基準
  - 信念
  - 作為
- devopsとは効率的に仕事をするために、社会構造、文化、技術を革新する方法を見つけること。

```
【水研の場合】

社会構造の革新：サイロ化の解消とオンプレミスからの脱却
文化の革新：資源評価報告書文化からmdによる簡潔な報告書へ、そしてTidyデータによるデータハンドリング
技術の革新：ExcelWordからRとプレーンテキストへ
```

## 2.2 devopsの方程式

```
"自分のことを新しいと思っている運動には、古くないすべてのものを支持しようとする危険性がある
 (リー・ロイ・ビーチ他「Natuiralistic Decision Making and Related Research Lines」) (p.13)"
```

- 本書は「唯一無二の正しい方法」を示すものではない
- 誤解やアンチパターンも大事だが、成功例がどのように機能したかが重要
- devopsは開発(dev)と運用（Ops)のみならず組織全体に応用すべき
  - 思考を開発と運用チームのみに限定してはいけない。そのような運動はdevopsではないし、むしろ **害** を与える

```
【水研の場合】

「devopsは新しく革新的な文化だから良いものだ！」と言っているよあの人たち・・・

と思われないことが大事。新しいものが良いわけでない。良さを相手の視線に合わせて伝える必要がある。
```

## 2.2.1 通俗モデルとしてのdevops

```
【通俗】

世間一般の人々にわかりやすく親しみやすいこと。一般向きであること。また、そのさま。
（小学館 デジタル大辞林）
```

- devopsという言葉は普及したが、そのぶん不用意に使われるようにもなった
- なんとなく雰囲気としてわかる
- しかしdevopsは抽象的な考え
  - 定義は人によってさまざま
- devopsを定義するより、**devopsがもたらす効能** について語るべきであろう
  - どんなに良いものであっても、それが可視化できないと人はついてこない

## 2.2.2 古い見方と新しい見方

会社には古い見方と新しい見方がある

- 古い見方(非難文化)
  - ヒューマンエラーは属人問題
  - 腐ったリンゴが問題を犯す
  - ミスを犯す問題or人を除去・修正することで対応

- 新しい見方(devops文化)
  - ヒューマンエラーは構造問題
  - システムに問題があるから人はエラーを犯す
  - 合理的に問題を把握し修正することで対応

新しい文化ではすべてのことが **学習機会** となる。
- チーム内の透明性向上、信頼向上
- ダメージコントロールと防止
- 新しい問題解決に取り組める。イノベーション促進

```
【個人見解】
ヒューマンエラーをさせてしまう環境自体が問題であろう。
ヒューマンエラーは、機能問題以外の問題を炙り出す。
再度にわたるH.エラーは、根本的なシステムやアプローチの問題を炙り出す。
大きな前進へのきっかけとなる。

ケアレスミスに注意せよ、とよく言われる。
ケアレスミスが起こり得ないような仕組みを作ることで、各人に心理的・時間的余裕が生まれる。
```
## 2.2.3 devops共同体
- Devopsは共同体として仕事をすすめる。
  - 信頼関係が必要
  - 非難の応酬を用いてはならない。

---

### ロッククライマーの例

ロッククライミングは登る人（クライマー）と、落下しないようハーネスを確保する人（ビレイヤー）の共同体で進められる。

#### 手順
1. クライマーの保持の申請
1. ビレイヤーの保持の確保と伝達
1. クライマーの登攀許可の申請
1. ビレイヤーの許可

登攀するという目的が共有されており、そのためのルートは柔軟に決定され、修正される。そして、進行役と許可役の２つの立場による密なコミュニケーションのサイクルが信頼を生む。

仕事を進めていく側は、現場で物事をみているからこそ進むことが出来る。一方、その仕事を支え、許可を出すものは大局的な視野で物事を見ることが出来る。そして双方がそれぞれの視野からベストなルートを選定することができ、ダイナミックなルート修正も可能となる。

---

### Sparkle Corpの例

Sparkle社のある部署ではベテラン社員（大佐）と新人（ジョージ）が共同で仕事をしている。ここでは、「エンドユーザーのための利益となるサイトの機能実装」が共通認識の目標として存在している。

大佐はジョージに仕事を投げるが、お互いの仕事はサイロ化していない。大佐は価値やプロセス、信念などをジョージに伝える。ジョージは助けやわからない点について大佐にそれを伝える。両者は仕事の進捗について報告しあいながら進むことができ、明確なコミュニケーションによって安心と信頼を維持する。


明確な意思疎通によって技術的・心理的・構造的な問題を削減することが出来る。


```
【個人見解】

devops共同体には以下の要素が重要だろうと考えてみた。
- 明確に定義された目標の共有(DOC?)
- その場その場でのコミュニケーション
- 理解をダイナミックに調整・修正。直すこと、削除する勇気

【水研の場合】

明確に定義された目標の共有：水産資源の利用と保全
その場でのコミュニケーション：サイロ化
理解をダイナミックに調整・修正：伝統的な.xlsを引き継ぐウナギのタレ方式
```

> 誰かがその機能を担当するだろうとか、そのうち終わるだろうといった考えは改める。そしてソフトウェアの本来の動作を妨げているバグを修正する。本番環境でものごとが期待どおりに進まないときは、プロセスを直しドキュメントにも反映する。(p.16)

本章のdevops共同体の考えは本書全体で一貫している。このような文化的側面が技術的側面と合わさり、共通の相互理解を構築する。明確に、恐れずに、目的を共有しながらコミュニケーションをとることの大事さを胸に刻むべきであろう。
