# Day059 — 見積もり条件ずれ見張り

> 複数見積もりの前提差を見つけやすくするためのツールです。
>
> Complexity Tier: medium
>
> Selected Components: none
>
> Family / Mechanic: quote_assumption_diff / diff_grid
>
> Input -> Output: assumption_rows -> assumption_heatmap
>
> Audience Promise: 比べるべき違いと確認すべき点がすぐ分かる。

## 使い方

このツールでできること
複数見積もりの前提差を見つけやすくするためのツールです。

こんな時に使います
複数社の見積もりが揃っても条件差が読めない時に使います。

使い方
1. 見積もりを並べる
2. 条件行を足す
3. 差と聞き返しを見る

## Story

- [制作ストーリー](./STORY.md)
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.
- Publish hook: 項目と前提を自分で足し引きしながら並べると、価格差より先に抜け条件と聞き返し項目が見える。

## Demo

🌐 [GitHub Pages](https://ryo909.github.io/ai-dev-day-059/)

---

Day059 / #100日開発
