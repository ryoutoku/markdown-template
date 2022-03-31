# markdown-template

VSCode を用いて markdown でドキュメントを作成する際の設定テンプレート。

## 使用環境

- VSCode
- node version 14.17.1
- textlint
  - comments
  - preset-ja-technical-writing
  - preset-ja-spacing
  - spellcheck-tech-word
  - textlint-rule-preset-ja-technical-writing
  - textlint-rule-spellcheck-tech-word
- markdownlint

## 環境設定

```bash
npm init --y

npm i -D \
    textlint \
    textlint-rule-preset-ja-spacing \
    textlint-rule-preset-ja-technical-writing \
    textlint-rule-spellcheck-tech-word \
    textlint-filter-rule-comments \
    markdownlint
```
