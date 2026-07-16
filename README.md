# Dahlia 営業提案用デモサイト

和歌山県紀の川市の外構事業者「Dahlia」様向けに制作した、1ページ型の非公式デモサイトです。

## 確認済み情報

- 事業者名: Dahlia
- 業種: 外構
- 所在地: 〒649-6418 和歌山県紀の川市久留壁133-2
- Instagram: [@dahlia_green_object](https://www.instagram.com/dahlia_green_object/)
- Googleマップ: 参照スプレッドシート記載の検索リンク

電話番号、営業時間、定休日、具体的な施工対応エリアは公開情報から確認できなかったため掲載していません。

## デモとして仮作成した内容

- キャッチコピー、説明文、強みの表現
- 新築外構、門まわり、カーポート、庭・植栽などのサービス例
- 施工対応エリアの説明
- 全ての施工イメージ画像

画像はAI生成による一般的な参考イメージで、Dahlia様の実施工写真ではありません。サイト上にもその旨を明記しています。

## 編集箇所

- 本文・リンク: `index.html`
- 色・レイアウト・レスポンシブ表示: `styles.css`
- モバイルメニュー: `script.js`
- 画像: `assets/`

## ローカル確認

静的HTMLのため、任意のローカルサーバーで公開できます。

```bash
python3 -m http.server 8080
```

ブラウザで `http://localhost:8080` を開いてください。

## Cloudflare Pages

静的HTMLサイトのためビルドは不要です。

- Framework preset: `None`
- Build command: 空欄
- Build output directory: `/`（リポジトリのルート）

GitHubリポジトリをCloudflare Pagesへ接続し、上記設定でデプロイします。

## 検索エンジン対策

`index.html` に次を設定しています。

```html
<meta name="robots" content="noindex, nofollow, noarchive" />
```

これは検索エンジンへの登録を抑制する指示であり、URLへのアクセス制限ではありません。
