# 防災減災ポッドキャスト

このリポジトリは、防災減災ポッドキャスト番組の公式ウェブサイトです。

## 概要

防災・減災に関する知識を、わかりやすく、楽しくお届けするポッドキャスト番組のウェブサイトです。

### 掲載内容

- 📻 番組紹介
- 📚 配信済みエピソードのアーカイブ
- 📅 今後の配信予定
- 📢 お知らせ

## ファイル構成

```
mywebsite/
├── index.html          # ホームページ
├── archive.html        # エピソード一覧ページ
├── styles.css          # スタイルシート
├── images/             # 画像フォルダ（ポッドキャストカバーなど）
└── README.md           # このファイル
```

## セットアップ

このサイトはGitHub Pagesで公開されています。

**公開URL:** `https://ajackassboy.github.io/mywebsite/`

## カスタマイズ方法

### 番組情報の更新

`index.html` の以下の部分を編集して番組情報を更新してください：

- **番組紹介テキスト**: `<section id="about">` 内のテキスト
- **配信予定**: `<section id="schedule">` 内のスケジュール項目
- **お知らせ**: `<section id="news">` 内のニュース項目

### エピソード情報の追加

`archive.html` に新しいエピソード情報を追加してください：

```html
<article class="episode-card">
    <div class="episode-number">第XX回</div>
    <h3>エピソード名</h3>
    <p class="episode-date">YYYY年MM月DD日配信</p>
    <p class="episode-description">
        エピソードの説明文
    </p>
    <div class="episode-meta">
        <span class="episode-duration">約XX分</span>
        <a href="#" class="listen-btn">聴く</a>
    </div>
</article>
```

### ポッドキャストカバー画像の追加

1. `images/` フォルダを作成（まだない場合）
2. ポッドキャストのカバー画像を `images/podcast-cover.jpg` として保存
3. `index.html` の `<img src="images/podcast-cover.jpg">` を確認

## スタイルのカスタマイズ

`styles.css` で以下の色をカスタマイズできます：

- **ヘッダー背景色**: `#2c3e50`
- **アクセント色**: `#e74c3c` (赤), `#3498db` (青)
- **メインカラー**: グラデーション `#667eea` 〜 `#764ba2`

## 配信プラットフォームへのリンク

`index.html` の footer セクションと`styles.css` の `.social-links` を編集して、以下のプラットフォームへのリンクを追加してください：

- Spotify
- Apple Podcasts
- Google Podcasts
- Amazon Music
- その他の配信プラットフォーム

## ライセンス

© 2024 防災減災ポッドキャスト. All rights reserved.

## お問い合わせ

番組に関するご質問やご意見は、お知らせセクションの連絡先までお願いします。
