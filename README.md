# rule_slack
slackのルール作り

## 共有チャンネル（デフォルトで全員が入っている）

- Generalチャンネル：
  - `# general`

- randomチャンネル：雑談とか、ご飯のお誘いとか
  - `# random`

- 研究室のリソース関連：PCの設定とか、iisアカウント登録とか
  - `# lab-resources`

- なんでも質問OK、善意で回答
  - `# askMeAnything`

- 新規加入メンバー向け：
  - for_new_comers

- ボット：redmineやgitなど想定
  - `# bot-*`
  - `# bot-remind`

- 秘書さん問い合わせ：精算、申請などを行う
  - `# secretary`

```
From secretary: 
【＠channel：*** 】
- Urgent
- Important
- Announce 
```
```
From members:
【@rieko: *** 】
- 出張
- 経費
- お尋ね
```

## 個別チャンネル命名規則

- チーム：今後BCを3チーム体制で行うことを想定し、チームごとに立てる。シニア/学生、などもあり得るか。
  - `# team-*`
  - `# team-imageBC`

- プロジェクト：プロジェクトごとに立てる
  - `# pj-*` 
  - `# pj-mycityreport`

- イベント運営：イベントごとに立てる
  - `# event-*`
  - `# event-s4d`

- インターン、アルバイト等：1人一つ立てる
  - `# intern-*`
  - `# intern-deeksha`

- 広報（Facebook含む）
  - `# website-update`


## 運用ルール

- @channel/@hereは全員に通知が表示されるため、極力避ける
- 連続投稿禁止（検索性、スター、ピンの効率的な運用のため。）
- 長文はスニペットにまとめて投稿する
- 複数人が別々の内容を話し合っていて、情報が錯綜しそうな場合、続ける会話が他メンバーの目に触れる必要がない場合にはスレッドを立てる
- 「了解」、「確認しました」の投稿は避け、アクションで対応する
- 不要になったチャンネルはこまめに削除する
- 基本的にDMは使わない
- メンションの後「くん」「さん」「先生」不要
