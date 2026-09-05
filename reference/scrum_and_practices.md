# Scrum公式要素と補助プラクティスを分ける

Scrumは意図的に不完全なframeworkです。現場で役立つ多くの技法を組み合わせられますが、それらをScrum必須ルールとして教えないことが重要です。

## Scrum Guideが定義する中核

### Accountabilities
- Product Owner
- Scrum Master
- Developers

### Events
- Sprint
- Sprint Planning
- Daily Scrum
- Sprint Review
- Sprint Retrospective

### Artifacts
- Product Backlog
- Sprint Backlog
- Increment

### Commitments
- Product Goal
- Sprint Goal
- Definition of Done

## よく併用されるプラクティス

| Practice | 使いどころ | Scrum必須？ |
|---|---|---|
| User Story | 利用者価値の会話を始める | いいえ |
| Acceptance Criteria | PBI固有の期待を明確にする | いいえ |
| Story Point | 相対的なsizeの会話 | いいえ |
| Planning Poker | 見積認識差を見つける | いいえ |
| Velocity | 過去実績をplanning参考にする | いいえ |
| Burndown | 残量を可視化する | いいえ |
| Kanban board | Workflowを可視化する | いいえ |
| Definition of Ready | 着手前のチーム基準 | いいえ |
| MVP | 仮説検証範囲を小さくする | いいえ |
| Inception Deck | 初期の方向・制約を会話する | いいえ |
| Sprint 0 | 事前準備期間を呼ぶ慣習 | いいえ |

## DoRとDoD

### Definition of Done

Scrum公式のCommitmentです。Incrementの品質と透明性に関わります。

### Definition of Ready

便利なチームルールになり得ますがScrum公式要素ではありません。

DoRを厳格にしすぎると、

> 仕様が100%決まるまで着手しない

というmini-waterfallへ戻ることもあります。

「会話を始められるだけの情報があるか」という軽量な基準として使うなど、目的を明確にします。

## Story PointとVelocity

利用しても構いませんが、目的は人を評価することではありません。

避けたい使い方：
- Aさんは30pt、Bさんは15ptだからAさんの方が優秀
- Team Xは80pt、Team Yは40ptだからXが2倍生産的
- 毎Sprint Velocityを上げることを目標にする

数字をKPI化すると、point自体を大きくする誘因が生まれます。

## Inceptionや事前準備

プロジェクト開始前に方向性・環境・ルールを整えることは有用です。

ただし「Sprint 0を必ず実施するのがScrum」とは教えません。

公式Scrumと組織独自のdelivery processを分けて説明します。
