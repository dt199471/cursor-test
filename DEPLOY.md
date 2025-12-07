# デプロイ方法

このオセロゲームをクラウドにデプロイする方法です。

## Vercel でデプロイ

1. [Vercel](https://vercel.com) にアカウントを作成
2. GitHubリポジトリを接続
3. ブランチを選択（claude, codex, gemini, composer のいずれか）
4. 自動的にデプロイされます

または、Vercel CLIを使用：
```bash
npm i -g vercel
vercel
```

## Netlify でデプロイ

1. [Netlify](https://netlify.com) にアカウントを作成
2. GitHubリポジトリを接続
3. ブランチを選択
4. 自動的にデプロイされます

または、Netlify CLIを使用：
```bash
npm i -g netlify-cli
netlify deploy --prod
```

## GitHub Pages でデプロイ

1. リポジトリの Settings > Pages に移動
2. Source でブランチを選択
3. `/ (root)` を選択
4. Save をクリック

## Cloudflare Pages でデプロイ

1. [Cloudflare Pages](https://pages.cloudflare.com) にログイン
2. GitHubリポジトリを接続
3. ブランチを選択
4. Build command: なし
5. Build output directory: `/`
6. Deploy をクリック

