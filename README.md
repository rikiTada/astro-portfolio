# Astro で Portfolio と Blog を構築

## 目標

- Astro でポートフォリオとブログを構築する
- ブログを microCMS で管理する
- Vercel を使ってデプロイする

## 準備するもの

- astro
- microCMS
- GitHub
- vercel
- vscode

## 手順

1. vscode インストール
2. GitHub アカウント作成
3. astro の環境構築
4. scss インストール
5. vercel インストール
6. microCMS アカウント作成

## 1.vscode インストール

## 5.vercel

[astro に vercel を追加](https://docs.astro.build/ja/guides/deploy/vercel/)

## SCSS

```npm
npm i sass
```

![sass install](image/README/image.png)

## 6.microCMS

[microCMS => Astro-Blog](https://blog.microcms.io/astro-microcms-introduction/)
![microCMS Site](image/README/image-1.png)
![3step](image/README/image-2.png)
src/library/microcms.ts
![ts](image/README/image-3.png)

---

.env
MICROCMS_SERVICE_DOMAIN=<YOUR_SERVICE> //.microcms.io は含まない値
MICROCMS_API_KEY=<YOUR_KEY_VALUE>
![Alt text](image/README/image-4.png)
![Alt text](image/README/image-5.png)
![Alt text](image/README/image-6.png)

## 注意点

1. pages/[blogId].astro を `[blogid].astro` にしていたためエラーが発生。しっかりスネークケースを使用すること。
