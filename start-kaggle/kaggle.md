<!-- $theme: gaia -->

# ==本当に簡単なkaggleの始め方==

### @yukinagae

<!-- page_number: false -->

---

# Agenda

1. kaggleとは？
2. データ分析のトレンドの変化
3. kaggleの仕組み
4. なぜkaggleをやるの？
5. やってみた(｀・ω・´)

<!-- page_number: true -->

---

# ==1.== kaggleとは？

---

### 世界最大の機械学習・データ分析の
### コンペを主催するプラットフォーム

# ![center](./images/kaggle.png)

---

# つまり

---

<!-- *template: invert -->

# データサイエンティストの
# 世界最強を決める大会

---

## kaggleの規模

* ユーザ数: 50万以上
* 国: 190カ国以上

らしい(｀・ω・´)

---

# ==2.== データ分析トレンドの変化

---

<!-- *template: invert -->

# 理論（theory）
# ↓
# 実践（practice）

---

# 昔

* 理解するのが大事（theory）

↓

# 今

* 実践・役立つのが大事（practice）


---


# 実践を重視している具体例
* kaggle
	* コンペ
	* ノウハウの共有（コード・ディスカッション）
	* データの共有・公開
* fast.ai
	* deep learning for coders（開発者の深層学習）
	* 理論より実践、SOA（state of art: 最先端）


---

![andrew](./images/andrew.jpeg)
From: [deeplearning.ai: Announcing new Deep Learning courses on Coursera](https://medium.com/@andrewng/deeplearning-ai-announcing-new-deep-learning-courses-on-coursera-43af0a368116)

---

# AI社会による生活の向上

by Andrew Ng (AIや機械学習の有名な教授・教師)

> *I hope we can build an AI-powered society that gives everyone affordable healthcare, provides every child a personalized education, makes inexpensive self-driving cars available to all, and provides meaningful work for every man and woman. An AI-powered society that improves every person’s life.*



---


# ==3.== kaggleの仕組み

---

## 大まかな流れ

1. 主催者（企業など）がコンペを主催する
	a. データを準備
	b. 問題を定義する
2. 参加者は様々な手法を使ってベストなモデルを構築し、予測を提出する
	* スコアやランキングが分かる
4. 主催者は、精度が高い予測に賞金を払う


---

# ==4.== kaggleをなんでやるの？

---

# 参加者のメリット


* 様々なデータに触れられる（企業が実データを提供してくれる。レアい）
* 他の参加者から学べる
* 入賞すれば賞金 + 良い仕事をGET！
* 楽しい
* ~~ギャンブル感覚~~

---

# 主催者側のメリット

* 世界中のデータサイエンティストが問題解決の手法を試行錯誤してくれる
* ブランディング・PR
* データサイエンティストの採用

---

# が、しかし

---

# kaggle依存の副作用

# （kaggle is drug）

# ![40% center](./images/kaggle_addicted.png)

---

# コンペが始まると仕事しなくなる人たち

![50% center](./images/not_work.png)

---

# ということで

---

# ==5.== 早速kaggleをやってみた(｀・ω・´)

---

## 1. コンペを選ぶ

<img src="./images/competition_list.png" alt="コンペを選ぶ" width="800"/>

---

最近始まったばかりのコンペ(｀・ω・´)

<img src="./images/ga_competition.png" alt="ga" width="800"/>

---


## 2. コンペの内容を読む


1. 概要: 大まかに把握
1. 評価指標: これが一番大事(｀・ω・´)
1. 賞金: できればほしいよね
1. 期限: 時間厳守
1. データ: だいたいCSVファイル（BigQueryも）

---

## 3. 他の参加者から学ぶ
	
1. コード（kernel）
1. ディスカッション（discussion）

![30% center](./images/kernels.png)

---

いろんな人がコードを載せてくれてるので助かる

![30% center](./images/code.png)

see: [Simple Exploration+Baseline - GA Customer Revenue | Kaggle](https://www.kaggle.com/sudalairajkumar/simple-exploration-baseline-ga-customer-revenue)

---

## 4. 他の参加者の方法を真似てみる
コードをパクってローカルPCで実行するだけの簡単なお仕事(｀・ω・´)

![25% center](./images/imitation.png)

---

## 5. 助け合う <= New!
ちょうどライブラリのバージョンで上手く動作しなかったので、上手くいった方法を教え合う(｀・ω・´)

![50% center](./images/comment.png)

---

## 6. めんどくさいので人のコードをforkする

![50% center](./images/fork_original.png)

---

forkしたコードを実行するだけ(｀・ω・´)

![50% center](./images/fork.png)

---

実行中

![50% center](./images/fork_running.png)

---


## 7. 予測を提出する

![50% center](./images/submission.png)

---

## 8. スコアとランクを確認

689位（全1,031チーム）

ちーん(｀・ω・´)

![100% center](./images/result.png)


---

# 結局言いたいのは

---

<!-- *template: invert -->

# パクった後が勝負

---


# まとめ

* kaggleはデータサイエンティストのNo.1を決める大会
* 理論より実践のトレンド
* とりあえず人のコードをパクって頑張る
* kaggleは沼(｀・ω・´)


---


# 参考資料

* [Kaggle - Wikipedia](https://en.wikipedia.org/wiki/Kaggle)
* [What is Kaggle, Why I Participate, What is the Impact?](https://www.kaggle.com/getting-started/44916)
* [fast.ai · Making neural nets uncool again](http://www.fast.ai)
* [deeplearning.ai: Announcing new Deep Learning courses on Coursera](https://medium.com/@andrewng/deeplearning-ai-announcing-new-deep-learning-courses-on-coursera-43af0a368116)


---

# おわり(｀・ω・´)

## ようこそkaggle沼へ

# ![center 30%](./images/me.png)