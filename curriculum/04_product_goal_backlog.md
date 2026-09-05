# 第4章：Product GoalとProduct Backlog

## ゴール

**「最初に全要件を確定する」から、「目標に向けて次に価値が高いことを選ぶ」へ考え方を切り替える。**

## Product Goal

Product Goalは、Scrum Teamが計画するための長期的な目標です。

例：

> 学園祭の来場者が、現在地から自分に合う出店を迷わず見つけられるようにする。

これは機能一覧ではありません。

悪い例：

```text
ログイン、検索、地図、口コミ、お気に入りを全部作る
```

これは「何を作るか」であって、「どんな価値を実現したいか」が弱い状態です。

## Product Backlog

Product Goalに向かうために必要と考えている作業を、**創発的かつ順序付けられたリスト**として管理します。

```text
上: 近いうちに取り組む、より明確
|
|  詳細化し続ける
|
下: 将来候補、まだ粗くてもよい
```

最初から全部を同じ詳細度まで仕様化する必要はありません。

## Refinementは継続的な活動

Product Backlog Itemを、

- より小さくする
- より明確にする
- 必要な情報を足す
- sizeを検討する

といった活動を継続します。

RefinementはScrumの正式なeventではありません。

## User Storyは便利だが必須ではない

例：

> 来場者として、現在地に近い出店を見たい。歩き回らず店を決めたいから。

この形式は価値を考えるのに便利ですが、Scrum Guideが要求する書式ではありません。

同様に、Story Pointも必須ではありません。

## Acceptance Criteriaは何のため？

PBIについて「何を期待しているか」を共有する助けになります。

例：

- 現在地を許可した場合、近い順に出店が表示される
- 位置情報を拒否しても一覧は利用できる

ただしAcceptance CriteriaとDefinition of Doneは別物です。

```text
Acceptance Criteria
→ このPBI固有の期待

Definition of Done
→ Increment全体に共通する品質基準
```

## ミニ演習

次を「機能名」ではなく「価値」へ書き換えてください。

> QRコード読み取り機能を作る。

誰が、何のために使うのかを考えると、別の解決策も提案できるようになります。

## 完了チェック

- [ ] Product Goalと機能一覧を区別できる
- [ ] Product Backlogを固定仕様書として説明していない
- [ ] Refinementが継続的活動であり正式eventではないと説明できる
- [ ] User Story / Story PointがScrum必須ではないと説明できる

---

前: [第3章](03_scrum_team.md)  
次: [第5章 Sprint Planning](05_sprint_planning.md)
