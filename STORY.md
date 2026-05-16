# Day084 Story — Doorstep Pickup Shelf

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day084専用にテーマをseed固定して再生成時の見た目を安定化
- utility用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: doorstep_pickup_staging
- Mechanic: tray_sort
- Input/Output: return_items -> checkout_trays
- Audience Promise: 渡す直前の開封確認を減らせる。
- Publish Hook: 荷物ごとの相手、時刻、不足物を入れると、玄関の棚に置く順と赤い抜けが出る。
- Complexity Tier: small
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
Day084｜玄関受け渡し棚
玄関で渡す荷物を並べるツールです。
