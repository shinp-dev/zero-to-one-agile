# 第7章：Increment / Definition of Done / Sprint Review

## ゴール

**DoneなIncrementとSprint Reviewを、検収・承認・リリースゲートと混同せず説明できる。**

## Increment

Incrementは、Product Goalへ向けた具体的な一歩です。

複数のIncrementを1 Sprintで作ることもできます。

## Definition of Done

Definition of DoneはIncrementが必要な品質基準を満たす状態を正式に説明するものです。

例：

- 主要自動テストが通っている
- 必要なレビューが完了している
- セキュリティ上の重大な既知問題がない
- 利用可能な状態へ統合されている

チームの状況に合わせて定めますが、**Doneを名乗るなら共通の品質基準を満たす**必要があります。

## 「テストは次Sprint」はDoneではない

```text
実装完了
でもテスト未実施
```

なら、その作業をDoneなIncrementとして扱わない、という透明性が大切です。

品質を下げてSprint Goal達成を装うのは、Scrumの検査を壊します。

## Sprint Review

Sprint Reviewの目的は、**Sprintの成果を検査し、今後の適応を決めること**です。

Scrum Teamとstakeholdersが、

- 何が達成されたか
- 環境や利用者ニーズがどう変わったか
- Product Goalへの進捗はどうか
- 次に何をするべきか

を一緒に検討します。

単なるプレゼン会ではなくworking sessionです。

## Reviewはリリース承認ゲートではない

DoneなIncrementはSprint終了前でも価値を届けられます。

```text
完成
↓
Sprint ReviewでPOが承認
↓
やっとリリース可能
```

という固定ゲートをScrumが要求しているわけではありません。

実務上、法務・運用・組織ルールによる承認が必要なことはあります。しかし、それとScrumのSprint Reviewの目的は分けて考えます。

## 受け入れ基準とPO

POは価値や期待を明確にする重要なaccountabilityを持ちますが、Sprint Reviewを「PO一人による合否判定会」にしません。

Stakeholderから得た新しい情報をProduct Backlogへ反映することが重要です。

## 完了チェック

- [ ] Definition of Doneを品質の共通基準として説明できる
- [ ] 未テストの作業をDoneとして扱わない理由を説明できる
- [ ] Sprint Reviewをデモだけの会議として説明していない
- [ ] Sprint Reviewをリリースゲートと説明していない

---

前: [第6章](06_daily_and_adaptation.md)  
次: [第8章 Retrospective](08_retrospective.md)
