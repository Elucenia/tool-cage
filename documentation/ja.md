<!-- ELUCENIA technical documentation · cage · ja · no clinical/professional/rights approval -->

# CAGE質問票

[条件・出典・許諾](https://elucenia.org/ja/tools/cage)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### C – 飲酒を減らすか、やめるべきだと感じたことがありますか？

`c`

### A – 飲み方への他人の批判でいらいらしますか？

`a`

### G – 普段の飲み方に罪悪感を感じますか？

`g`

### E – 緊張や二日酔いを和らげるため朝に飲酒しますか？

`e`

## 方法の版

CAGE/Ewing 1984：4二値質問、0～4、閾値≥2、ポルトガル語Masur–Monteiro 1983

## 記載された計算式

回答ごとに1点 “はい”: Cut down (減らす), Annoyed (批判に苛立つ), Guilty (罪悪感), Eye-opener (起床時に飲酒)。カットオフ：≥ 2.

## 限界・対象集団

アルコールに関する問題をスクリーニングする短い質問票で、その後に臨床評価を行います。引用されたブラジルの妥当性研究は精神科病院に入院した男性を対象としました。他の集団で同じ性能があると仮定してはいけません。このコホートの構成は、性別による普遍的な除外ルールではありません。

## 参考文献

- [Ewing JA. Detecting alcoholism: the CAGE questionnaire. JAMA, 1984.](https://doi.org/10.1001/jama.1984.03350140051025)

- [Masur J, Monteiro MG. Validation of the "CAGE" alcoholism screening test in a Brazilian psychiatric inpatient hospital setting. Braz J Med Biol Res, 1983.](https://pubmed.ncbi.nlm.nih.gov/6652293/)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
