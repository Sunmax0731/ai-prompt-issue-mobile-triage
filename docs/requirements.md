# 要件定義

| 項目 | 内容 |
| --- | --- |
| Rank | 79 |
| Domain | AndroidApp |
| Idea No. | 7 |
| Repository | ai-prompt-issue-mobile-triage |
| 主な公開先 | Google Play |

## 背景

PC前でしか次の作業候補やプロンプトを整えられない。

## 目的

AI指示文、Codexテンプレ、GitHub Issueメモを外出先で整理する。 入力、確認、履歴保存、次アクションを同じ作業単位で扱えるようにする。

## 必須要件

- mobile triage item を複数件まとめて検証できる。
- required fields: `id`, `title`, `promptPath`, `issueRef`, `triageStatus`, `owner`。
- warning field: `syncNote`。
- 代表シナリオ、QCDS metrics、docs ZIP、release evidence を再生成できる。
