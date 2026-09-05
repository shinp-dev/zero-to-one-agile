# Scrum状況判断チェック

暗記ではなく「この状況ならどう判断するか」を考えます。

## Case 1：緊急要望

Sprint途中、重要顧客から新機能を今すぐ追加してほしいと言われた。

最もScrumに近い判断は？

A. Sprint Backlog変更禁止なので話を聞かない  
B. POがDevelopersへ即座に割り込ませる  
C. Sprint Goalへの影響を確認し、必要ならPOとDevelopersでscopeを明確化・再交渉する  
D. SMが一人で優先順位を決める

<details><summary>答え</summary>

**C**。Sprint Goalを守りながら、学習・環境変化に適応します。
</details>

## Case 2：テスト未完了

Sprint最終日、実装は終わったがDoDで必須のテストが未実施。

A. 90%できたのでDone  
B. POがOKならDone  
C. DoDを満たしていないのでDoneなIncrementとして扱わない  
D. ReviewでデモできればDone

<details><summary>答え</summary>

**C**。透明性を守ります。
</details>

## Case 3：Review前リリース

Sprint中盤にDoDを満たすIncrementができ、利用者へ出す価値がある。

A. Sprint Reviewまで絶対releaseできない  
B. Scrum上はReviewをrelease gateにする必要はない  
C. 次Sprintまで待つ  
D. SMの承認が必須

<details><summary>答え</summary>

**B**。組織の別ルールがあればそれには従いますが、Scrum Review自体はrelease gateではありません。
</details>

## Case 4：Dailyが報告会

毎朝、部長が参加し、各Developerの遅れをチェックして指示を出している。

問題は？

<details><summary>考えるポイント</summary>

Daily ScrumはDevelopersがSprint Goalへの進捗を検査し、計画を適応するeventです。管理者向けの個人進捗報告会にするとself-managementや透明性を損ねる可能性があります。
</details>

## Case 5：Velocity競争

2チームのVelocityを比較し、数値の低いチームへ改善命令を出した。

問題は？

<details><summary>考えるポイント</summary>

Story Pointの尺度はチーム内で相対的です。他チーム比較や人事評価へ使うと数値操作を誘発し、見積もり・計画の有用性を壊します。そもそもVelocityはScrum必須指標ではありません。
</details>

## Case 6：計画どおりだが価値がない

Sprint Goalと選んだ機能は予定どおり完成したが、Reviewで利用者から「この機能は使わない」と言われた。

これはSprint失敗？

<details><summary>考えるポイント</summary>

価値仮説が外れた可能性はあります。しかし早い段階で学べたこと自体は重要です。結果を隠さずProduct BacklogやProduct Goalへの進め方を適応します。「予定どおり作った」だけを成功指標にしないことがポイントです。
</details>
