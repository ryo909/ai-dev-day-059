# Day059 Story — Quote Assumption Watcher

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day059専用にテーマをseed固定して再生成時の見た目を安定化
- productivity用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: quote_assumption_diff
- Mechanic: diff_grid
- Input/Output: assumption_rows -> assumption_heatmap
- Audience Promise: 比べるべき違いと確認すべき点がすぐ分かる。
- Publish Hook: 項目と前提を自分で足し引きしながら並べると、価格差より先に抜け条件と聞き返し項目が見える。
- Complexity Tier: medium
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day059｜見積もり条件ずれ見張り
複数見積もりの前提差を見つけやすくするためのツールです。
