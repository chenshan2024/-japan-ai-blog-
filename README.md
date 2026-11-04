# 私たちは勉強が大好き（japan-ai-blog）

ITエンジニアが生成AIの最新動向と実践ノウハウを日本語で発信するブログ。

- サイト: https://japan.yujeff.dpdns.org
- 構成: Astro（静的サイト）+ Cloudflare Pages（GitHub 連携で自動デプロイ）
- 記事: `src/content/blog/*.md`（frontmatter: title, description, pubDate, tags, sources）

## 開発

```bash
npm install
npm run dev
npm run build   # 出力: dist/
```
