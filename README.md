# RK Playground

金城 竜一のポートフォリオサイトです。システムエンジニアとしての経歴と、自分で作った Web サイトを紹介しています。

公開 URL はまだ決まっていません。

## 技術

- フロントエンド: Astro, Tailwind CSS, TypeScript
- バックエンド: なし
- インフラ: Vercel（公開予定）
- ツール: Git, GitHub, Cursor

## ページ

トップページ（`src/pages/index.astro`）の構成です。

- Home
- About me
- Work experience
- Skills
- Portfolio

経歴とスキルの元データは `src/data/career.json` です。

## 開発

Node.js 22.22.3 以上が必要です。

| コマンド | 内容 |
| --- | --- |
| `npm install` | 依存関係を入れる |
| `npm run dev` | 開発サーバーを起動する（http://localhost:4321） |
| `npm run build` | 本番用ファイルを `dist/` に書き出す |
| `npm run preview` | ビルド結果をローカルで確認する |

サイト名やメタデータは `src/config.yaml`、フッターのリンクは `src/navigation.ts` です。

## ベース

このサイトは [AstroWind](https://github.com/arthelokyo/astrowind) の個人向けトップページ [`/homes/personal`](https://github.com/arthelokyo/astrowind/blob/main/src/pages/homes/personal.astro) をベースにしています。元のページは、このリポジトリの `src/pages/homes/personal.astro` に残しています。実際に公開するトップは `src/pages/index.astro` です。

テンプレートは MIT ライセンスです。詳細は [LICENSE.md](./LICENSE.md) を見てください。
