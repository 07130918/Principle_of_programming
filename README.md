# Principle of programming

## 1.前提
- コード自体がドキュメントである
- ソフトウェアは本質的に複雑であるため、完璧なものにはなりえない

## 2.原則
- KISS(修正容易性)
- DRY(ロジックやデータの抽象化でダブりを防ぐ)
- 単純性　＞　汎用性
- 書きやすさより、読みやすさ
- 関数の抽象度を揃える(抽象度の高い関数の中で具体的な処理を書くと可読性ダウン)
- 名前は、効果と目的を説明する

## 3.思想
- セオリー
```
  1. コミュニケーション
  2. シンプル
  3. 柔軟性
```
- 何のために"それ"を使うのか?
- ロジックと「ロジックが操作するデータ」はなるべく近くに置く(同じ関数、同じモジュール等)  
  → なぜなら、データとデータ操作の修正タイミングは同時期であることが多いから
- 抽象(現状まだあまり良く理解していない)
- カプセル化(データとロジックをグルーピング)
  → 影響度、何をしているか、が明確になり扱いやすくなる
- 情報隠蔽で複雑性を下げる
- パッケージ化(カプセル化したモジュール群をさらにグルーピングする)
- 関心の分離(MVC等)
- 充足性、完全性、プリミティブ性(表現が十分かつ完璧かつ純粋か)
- ポリシーと実装の分離(ポリシー: ビジネスロジックやモジュールに対する引数を選択する部分)  
  → ポリシーは不安定で実装は安定的
- インターフェースと実装の分離(インターフェース: 機能の定義)
- 定義は1度きり
- 分割統治(問題を小さくするためにモジュールの責務で分割する)
- 
