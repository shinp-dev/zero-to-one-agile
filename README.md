# Zero to One: Waterfall → Agile / Scrum

ウォーターフォール型の開発工程を学んだ学生が、**「アジャイルは計画しない」「スクラムは会議を増やす方法」ではなく、不確実な状況で短い周期の検査と適応を行う考え方・フレームワーク**として理解するための日本語教材です。

本教材は、2026年9月時点で現行の **Scrum Guide 2020** と **アジャイルソフトウェア開発宣言**を基準にしています。

## 最初に知ってほしいこと

ウォーターフォールとアジャイルは、単純な「古い / 新しい」「悪い / 良い」の関係ではありません。

```text
要件が比較的安定し、先に全体を決めやすい
→ 計画型の進め方が機能しやすい

利用者の反応や技術的不確実性が大きく、途中で学びが増える
→ 短い周期で検査・適応する進め方が機能しやすい
```

スクラムでも計画・設計・実装・テストを行います。違うのは、**全部を一度だけ順番に行うのではなく、価値を出せる小さな単位で繰り返す**ところです。

既に習った「要件・WBS・進捗会議・受入」などから見たい場合は、最初に [既習のウォーターフォール用語からScrumを見る](reference/waterfall_to_scrum_map.md) を開いてください。

## 学習順序

| 章 | テーマ | ゴール |
|---|---|---|
| [0](curriculum/00_from_waterfall.md) | ウォーターフォールから考える | 何が変わり、何が変わらないか説明できる |
| [1](curriculum/01_agile_values.md) | Agileの価値観 | Agileを「速く作る手法」と誤解しない |
| [2](curriculum/02_scrum_empiricism.md) | Scrumと経験主義 | 透明性・検査・適応を説明できる |
| [3](curriculum/03_scrum_team.md) | Scrum Team | PO / SM / Developersのaccountabilityを説明できる |
| [4](curriculum/04_product_goal_backlog.md) | Product Goal / Product Backlog | 価値と優先順位から「次に何をするか」を考えられる |
| [5](curriculum/05_sprint_planning.md) | Sprint / Sprint Planning | Sprint Goalを中心に計画できる |
| [6](curriculum/06_daily_and_adaptation.md) | Daily Scrum / 適応 | Sprint中に学びながら計画を更新できる |
| [7](curriculum/07_increment_review.md) | Increment / Review | DoneとReviewを「承認ゲート」と混同しない |
| [8](curriculum/08_retrospective.md) | Retrospective | プロダクトだけでなく働き方も改善できる |
| [9](curriculum/09_one_sprint_workshop.md) | 1 Sprint疑似体験 | 変更を受けてinspect / adaptを一周できる |

## 教材の地図

```text
既知: ウォーターフォール
  ↓ 比較
Agileの価値観
  ↓
Scrumの経験主義
  ↓
Product Goal / Backlog
  ↓
Sprint Goal / Sprint
  ↓
毎日の検査と適応
  ↓
Done Increment
  ↓
StakeholderとのReview
  ↓
Retrospective
  ↺ 次のSprintへ
```

## Scrum公式要素と「よく使う技法」は分ける

Scrum Guideが定義しているものと、現場でScrumと一緒によく使われる技法は別です。

**Scrumの中核**
- Scrum Team: Product Owner / Scrum Master / Developers
- Events: Sprint / Sprint Planning / Daily Scrum / Sprint Review / Sprint Retrospective
- Artifacts: Product Backlog / Sprint Backlog / Increment
- Commitments: Product Goal / Sprint Goal / Definition of Done

**よく併用されるがScrum必須ではないもの**
- User Story
- Story Point / Planning Poker / Velocity
- Definition of Ready (DoR)
- Kanban board / Burndown chart
- MVP
- Inception Deck
- Sprint 0という呼び方

詳しくは [Scrum公式要素と補助プラクティス](reference/scrum_and_practices.md) を参照してください。

## AI開発時代でも残る問い

AIによって実装が速くなっても、次の判断は消えません。

- 誰のどんな問題を解くのか
- 何を先に作ると価値や学びが大きいか
- 実際に使ってもらった結果、仮説は正しかったか
- 次に何を変えるべきか

実装速度が上がるほど、**間違ったものを速く大量に作らないための検査と適応**が重要になります。

## 演習

- [1 Sprint疑似体験シート](templates/sprint_workshop_sheet.md)
- [Working Agreementテンプレート](templates/working_agreement_template.md)
- [Product Backlog Itemテンプレート](templates/product_backlog_item_template.md)
- [基礎理解チェック](understanding_checks/00_scrum_basics.md)
- [状況判断チェック](understanding_checks/01_scenario_checks.md)

## リファレンス

- [既習のウォーターフォール用語からScrumを見る](reference/waterfall_to_scrum_map.md)
- [Scrum Quick Reference](reference/scrum_quick_reference.md)
- [Scrum公式要素と補助プラクティス](reference/scrum_and_practices.md)

## 公式資料

- Agile Manifesto 日本語版: https://agilemanifesto.org/iso/ja/manifesto.html
- Agile Manifesto 12 Principles 日本語版: https://agilemanifesto.org/iso/ja/principles.html
- Scrum Guides: https://scrumguides.org/
- Scrum Guide Downloads: https://scrumguides.org/download.html

## License

[MIT License](LICENSE)
