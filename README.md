# TAIKI LAB — Building Products & Ideas

プロダクトとアイデアをかたちにする、ひとり用の実験室サイト。

## 掲載プロジェクト

1. **AI Invest Radar** — https://ai-invest-radar.vercel.app/
2. **効能旅 (Kounou Tabi)** — https://socialweb-japan-tokyo.github.io/onsen-health-travel/

## GitHub Pages での公開手順

1. GitHub で新しいリポジトリを作成（例: `taiki-lab`）
2. この `index.html` をリポジトリ直下にアップロード（または push）
3. リポジトリの **Settings → Pages** を開く
4. **Source** を `Deploy from a branch` にし、`main` ブランチ / `/ (root)` を選択して保存
5. 数分後に `https://<ユーザー名>.github.io/taiki-lab/` で公開されます

### コマンドで push する場合

```bash
git init
git add index.html README.md
git commit -m "Launch TAIKI LAB site"
git branch -M main
git remote add origin https://github.com/<ユーザー名>/taiki-lab.git
git push -u origin main
```

## カスタマイズ

- 配色・フォントは `index.html` 内の `:root` CSS変数で変更できます
- プロジェクトを追加する場合は `Works` セクションの `.work` ブロックを複製してください
