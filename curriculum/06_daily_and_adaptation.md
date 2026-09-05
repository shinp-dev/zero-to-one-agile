# 第6章：Daily ScrumとSprint中の適応

## ゴール

**Sprint中の変更を「禁止」ではなく、Sprint Goalを守りながら適応する問題として判断できる。**

## Daily Scrumの目的

Daily ScrumはDevelopersのための15分イベントです。

目的は、

```text
Sprint Goalへの進捗を検査
↓
必要ならSprint Backlogを適応
↓
次の作業を調整
```

することです。

## 「昨日・今日・困りごと」は一例

よくある3質問：

- 昨日何をした？
- 今日何をする？
- 障害はある？

は使いやすい形式ですが、Scrum Guide 2020はこの形式を必須にしていません。

Sprint Goalへの進捗を検査し、実行可能な計画を作れるなら、Developersが構造を選べます。

## 重要：Sprint Backlogは変更してよい

誤解：

> Sprintが始まったらSprint Backlogは変更禁止。

正しくは、Sprint中に学習が進むにつれてSprint Backlogは更新されます。

ただしSprint中は、

- Sprint Goalを危険にする変更をしない
- 品質を下げない
- 学習が増えれば必要に応じてPOとscopeを明確化・再交渉する

という考え方になります。

## ケース

Sprint Goal：

> 現在地から近い出店を選べるようにする。

計画：

```text
位置情報取得
地図表示
距離順一覧
お気に入り
```

途中で地図APIが想定より重く、1週間では品質を満たせないと分かりました。

選択肢：

A. 最初に約束したので全部残業して作る  
B. Sprint Backlogは変更禁止なので何もしない  
C. Sprint Goalを満たせる「距離順一覧」を優先し、地図やお気に入りのscopeをPOと再調整する

このケースではCがScrumの検査・適応に近い判断です。

## Sprint取消し

Sprint Goalがobsolete（意味を失った）になった場合、Product OwnerがSprintをcancelできます。

単に「予定より遅れている」だけで簡単にcancelするものではありません。

## 完了チェック

- [ ] Daily Scrumを上司への進捗報告会と説明していない
- [ ] 3質問形式が必須ではないと説明できる
- [ ] Sprint Backlogは学習に応じて更新されると説明できる
- [ ] Sprint Goalとscopeを区別できる

---

前: [第5章](05_sprint_planning.md)  
次: [第7章 IncrementとReview](07_increment_review.md)
