# 翻訳ポリシー

## 文体

- 敬体（です・ます調）を使う

## 用語統一

| 英語 | 日本語訳 | 備考 |
|------|----------|------|
| Contribution / Contributor | コントリビューション / コントリビューター | |
| Issue | Issue | 英語のまま |
| Pull Request / PR | Pull Request / PR | 英語のまま |
| Branch | ブランチ | |
| Fork | フォーク | |
| Merge | マージ | |
| Commit | コミット | |
| Repository | リポジトリ | |
| Gracious Professionalism | Gracious Professionalism | 固有概念、英語のまま |
| Tech Tip | Tech Tip | 英語のまま |
| Servo | サーボ | |
| Motor | モーター | |
| Hub | ハブ | |
| Control Hub | Control Hub | 英語のまま |
| Expansion Hub | Expansion Hub | 英語のまま |
| Driver Station | Driver Station | 英語のまま |
| Robot Controller | Robot Controller | 英語のまま |
| OpMode | OpMode | 英語のまま |

## 翻訳しない表現

- コードブロック内のすべての識別子・関数名・定数名
- URL・リンクのhref値
- RST マークアップ（`:doc:`, `:ref:`, `**`, `*`, `` ` ``）の記法自体
- `*FIRST*` → `*FIRST*`（アスタリスク込みで保持）
- ファイル名・コマンド名・CLI オプション名
- PR 番号・issue 番号・GitHub ユーザー名
- Git, GitHub, RST, Sphinx, FTC, FIRST, API, SDK などの固有名詞

## PO ファイル形式のルール

- ファイルヘッダー（最初の `msgid ""` エントリ）は絶対に変更しない
- 既に翻訳済みの `msgstr` は変更しない
- RST マークアップは原文と完全に一致させる
- 1行の quoted string は 100 文字以内を目安に分割する
