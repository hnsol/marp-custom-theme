---
marp: true
theme: gaia_gd_noncode
size: 4:3
paginate: true
header: 'header text'
footer: 'footer text ex: 2022-mm-dd AAAAAAAA Inc.'

style: |
    section {
        font-size: 22px; }
    section strong {
        color: LightCoral; }
    section cite {
        font-style: normal;
        font-size: 50%;
        line-height: calc(0.25rem * 4);
        float: right;
        color: #628EC8; }
    section footnote {
        font-style: normal;
        font-size: 80%;
        color: #628EC8; }
    img[alt~="center"] {
      display: block;
      margin: 0 auto; }

---

<!-- _class: gaia lead -->
<!-- _paginate: false -->
<!-- _header: '' -->
<!-- _footer: '' -->

# h1: ドキュメントの標題

<br>

ノン・コーダーのための、Marpスライド サンプル集

<br><br>

2022-mm-dd
AAAAAAAA Inc.

<br>

このページは `<!-- _class: gaia lead -->`

---

<!-- _class: inside-title lead -->
<!-- _paginate: false -->
<!-- _header: '' -->
<!-- _footer: '' -->

## 代表的なスライド例

---

<!-- _class: lead -->
<!-- _paginate: false -->
<!-- _footer: '' -->

xxxxxxx株式会社

# T冬の学校 2022

<br>

2022-mm-24 & 25
AAAAAAA Inc.

![bg opacity:.5](https://images.unsplash.com/photo-1516015222231-943dc82860bc?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=987&q=80)

<br><br><br><br>

---

## 目次

- 時間割・資料一覧
- 開校式
- ステップ2｜重要度の評価
- ステップ3｜シナリオ群の定義
- ステップ4｜事業インパクト評価
- ステップ5｜対応策の定義
- ステップ0｜シナリオ分析をはじめるにあたって
- 閉校式
- 付録

<br>

※印刷配布は抜粋版です
　資料全体は共有フォルダに格納いたします


---

### グランドルール

#### Don'ts - これはやめてください

- **短時間集中型**で行いますので、メールや電話、内職はご遠慮ください
- やむを得ず受電・架電される場合、**室外で**お願いします

![h:150 center](https://cdn-ak.f.st-hatena.com/images/fotolife/m/masatora_bd5/20220207/20220207204536.png)

#### Dos - これはOKです

- 質問は随時OK
- あめ、ガム、飲み物などの軽食はOK
- 写真撮影は随時OK

---

### レクチャー01 シナリオ分析と気候関連財務情報開示

```
まずTCFD提言があり、その参考書（実践ガイド）を環境省が発行
```

TCFDは提言で「情報開示とそのためのシナリオ分析」を求めている。しかし簡単ではないので、環境省が具体的な手順を発行

![h:330 center](https://cdn-ak.f.st-hatena.com/images/fotolife/m/masatora_bd5/20211207/20211207160841.png)

<cite>出所：TCFD, 最終報告書 気候関連財務情報開示タスクフォースの勧告（2017）<br>　　　環境省, TCFDを活用した経営戦略立案のススメ（2021）</cite>

---

### 演習06 4℃/2℃@2050の定性的な予測（前半）

#### アウトプットイメージ

| 中分類 | 小分類 | 現在         | 4℃<br>（2050年） | 2℃<br>（2050年） | 出所   |
| ------ | ------ | ------------ | ---------------- | ---------------- | ------ |
| xxxx   | xxxx   | xxxxxxxxxxxx | xxxxxxxxxxxx     | xxxxxxxxxxxx     | xxxxxx |
| xxxx   | xxxx   | xxxxxxxxxxxx | xxxxxxxxxxxx     | xxxxxxxxxxxx     | xxxxxx |
| xxxx   | xxxx   | xxxxxxxxxxxx | xxxxxxxxxxxx     | xxxxxxxxxxxx     | xxxxxx |

#### ワーク（40分）

1. 小分類の右側に、`現在` `4℃` `2℃` `出所`欄を作成ください
1. 小分類単位で調査担当を決めてください（各人1項目）<br>→ レクチャー07をはさみます
1. `現在`および2050年（`4℃`/`2℃`）がどうなっているかと`出所`を記入ください

---

<!-- _class: FYR -->

### ご参考：複数の温度帯シナリオの説明でよく見かける図

![h:450 center drop-shadow:2px,2px,2px,gray](https://cdn-ak.f.st-hatena.com/images/fotolife/m/masatora_bd5/20211227/20211227173545.png)

<cite>出所：環境省, TCFDを活用した経営戦略立案のススメ（2021）</cite>

---

<!-- _class: inside-title lead -->
<!-- _paginate: false -->
<!-- _header: '' -->
<!-- _footer: '' -->

## サンプルコード集

---

<!-- _class: inside-title lead -->
<!-- _paginate: false -->
<!-- _header: '' -->
<!-- _footer: '' -->

## h2: ドキュメントの中表紙

<br><br>

標題は、見出しレベル1で、
中表紙は、見出しレベル2で、
各スライドのタイトルは、見出しレベル3で
表現することを想定しています

<br>

このページは `<!-- _class: inside-title lead -->`

---

### h3: スライドのタイトル

```
code: スライドのキーメッセージ→ひと通りワンスライドに盛り込んでみた
```

あのイーハトーヴォのすきとおった風、夏でも底に冷たさをもつ

- 箇条書き1、*イタリック*は赤字にならない、**強調箇所は赤字**になる
  - 小項目1、`pre: カギカッコで括る代わりに利用` (*1)

<footnote>
*1 footnote: 注釈を書くために利用
</footnote>

|     | 列A（左寄せ） | 列B（センタリング） | 列C（右寄せ） |
| --- | :------------ | :-----------------: | ------------: |
| 行1 | xxxxxxxxxx    |     xxxxxxxxxx      |    xxxxxxxxxx |
| 行2 | xxxxxxxxxx    |     xxxxxxxxxx      |    xxxxxxxxxx |

> blockquote。補足コメントや覚え書きとして利用

<cite>
出所：著者１・著者２, 書籍タイトル（yyyy）, 出版社
</cite>

---

### h3: 見出しレベル3

あのイーハトーヴォのすきとおった風、夏でも底に冷たさをもつ青いそら、うつくしい森で飾られたモリーオ市。

#### h4: 見出しレベル4

あのイーハトーヴォのすきとおった風、夏でも底に冷たさをもつ青いそら、うつくしい森で飾られたモリーオ市。

##### h5: 見出しレベル5

あのイーハトーヴォのすきとおった風、夏でも底に冷たさをもつ青いそら、うつくしい森で飾られたモリーオ市。

###### h6: 見出しレベル6

あのイーハトーヴォのすきとおった風、夏でも底に冷たさをもつ青いそら、うつくしい森で飾られたモリーオ市。

---

### 画像挿入の標準パターン

```
キーメッセージがここにある想定
```

補足テキストがここにある想定

![h:350 center drop-shadow:2px,2px,2px,gray](https://marp.app/assets/og-image.png)

---

### 画像挿入の別のパターン

```
背景に画像を貼ることもできます
```

- 左右分割、上下分割など、様々なレイアウトパターンがあります
- 画像に対してフィルタをかけることもできます
- 詳しくは公式ドキュメントをご参照ください
  - https://marpit.marp.app/image-syntax

![bg blur:5px opacity:.2](https://images.unsplash.com/photo-1572370824184-c2bc084af8d4?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=986&q=80)

![bg blur:5px opacity:.2](https://images.unsplash.com/photo-1643473232037-08736b56178d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1080&q=80)

![bg blur:5px opacity:.2](https://images.unsplash.com/photo-1583883175425-46dee3845e7f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=987&q=80)

---

### 出所の表記

```
出所の表記を統一したく、`<cite>`タグを追加しました
```

書く内容は、`Author, Title（year）, Publisher`の並びを想定しています

<cite>出所：著者１・著者２, 書籍タイトル（yyyy）, 出版社</cite>

<br>

<cite>出所：ウェブサイトのタイトル,<br> https://www.aaaaa.jp/bbbbbbbbbb/cccccccccc/dddddddddd</cite>

---

<!-- _class: FYR -->

### 【参考】スライド

```
参考スライドを挿入できると、実用的にはけっこう嬉しいです
```

本筋から少し脇にそれてしまうけれども、Appendixまで先送りせずに、本編の脇あたりに配置しておきたいスライドというのがあります。

- 箇条書き1、*イタリック*は赤字にならない、**強調箇所は赤字**になる
  - 小項目1、`pre: カギカッコで括る代わりに利用` (*1)

<footnote>
*1 footnote: 注釈を書くために利用
</footnote>

|     | 列A（左寄せ） | 列B（センタリング） | 列C（右寄せ） |
| --- | :------------ | :-----------------: | ------------: |
| 行1 | xxxxxxxxxx    |     xxxxxxxxxx      |    xxxxxxxxxx |
| 行2 | xxxxxxxxxx    |     xxxxxxxxxx      |    xxxxxxxxxx |

> このページは `<!-- _class: FYR -->`です

---

<!-- _class: gaia lead -->
<!-- _paginate: false -->
<!-- _header: '' -->
<!-- _footer: '' -->

# END
