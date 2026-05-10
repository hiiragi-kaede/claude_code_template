# CLAUDE.md

このファイルは、リポジトリ内のコードを扱う際に Claude Code (claude.ai/code) へのガイダンスを提供します。

## プロジェクト概要

<!-- 以下は自動生成させたclaude.mdの内容を例示 -->
<!-- 日本語UIのタスク管理シングルページアプリケーション。ビルド不要 — `index.html` をブラウザで直接開くか、任意の静的ファイルサーバーで3ファイルを配信するだけで動作します。

## ローカル起動方法

```bash
# いずれかの方法で起動可能
python3 -m http.server 8080
npx serve .
# または index.html をブラウザで直接開く
```

## アーキテクチャ

アプリケーション全体は3ファイルで構成されています。

- **`index.html`** — エントリーポイント。CDNからVue 3と`app.js`を読み込む。
- **`app.js`** — 全アプリケーションロジック（約377行）。Composition API（`setup()`）を使ったVue 3の`createApp`で構成。
- **`style.css`** — 全スタイル（約515行）。`:root`に定義したCSSカスタムプロパティを使用。

### 状態管理とデータフロー

すべての状態は`app.js`内のVue `ref()`・`computed()`として管理されます。タスクはキー`tm_tasks`のJSON配列として`localStorage`に永続化されます。バックエンドはありません。

**タスクオブジェクトの構造:**
```js
{
  id:          string,          // uid() — タイムスタンプ + ランダム値
  title:       string,
  description: string,
  status:      'todo' | 'progress' | 'done',
  priority:    'high' | 'medium' | 'low',
  dueDate:     'YYYY-MM-DD' | null,
  tags:        string[],
  createdAt:   ISO8601形式の文字列
}
```

### 定数 -->
