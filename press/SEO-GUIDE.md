# SALON GUIDE — SEO・集客拡大ガイド（戸塚ネイル特集）

Beagent 編集部 · 2026年6月

本ガイドは `salonlp.beagent.co.jp` の戸塚ネイル5選記事および SALON GUIDE 全体の検索流入・認知拡大のための実践手順です。

---

## 1. 今週中にやること（優先度：高）

### Google Search Console

1. [Google Search Console](https://search.google.com/search-console) に `salonlp.beagent.co.jp` を登録
2. DNS または HTML ファイルで所有権確認
3. **サイトマップ送信**: `https://salonlp.beagent.co.jp/sitemap.xml`
4. 「URL 検査」で戸塚記事を登録・インデックス登録をリクエスト  
   `https://salonlp.beagent.co.jp/press/areas/totsuka-nail-5.html`

### Xserver 再アップロード

- 最新 `salonlp-beagent.zip` を docroot 直下に解凍（二重フォルダにしない）
- `sitemap.xml` / `robots.txt` / `hero-nail.jpg` がルート・press 配下にあることを確認
- 古い `.htaccess` は削除

### 記事URLの拡散（SNS・LINE）

掲載サロン・Beagent 公式から同一 URL を共有：

```
https://salonlp.beagent.co.jp/press/areas/totsuka-nail-5.html
```

---

## 2. オンページ SEO（実装済み）

| 項目 | 内容 |
|------|------|
| title / description | 戸塚・ネイルサロン・ジェル・フィルイン・Reyel 等 |
| canonical | salonlp.beagent.co.jp（github.io ではない） |
| OGP / Twitter Card | hero-nail.jpg |
| JSON-LD | Article, ItemList, FAQPage, BreadcrumbList, BeautySalon×5 |
| FAQ | 5問（安い／フィルイン／パラジェル／相場／サクラス） |
| 内部リンク | ハブ・他エリア・for-salons |

---

## 3. オフページ SEO・拡大施策

### 被リンク（リンク獲得）

| 施策 | 具体 |
|------|------|
| Beagent 本体 | beagent.co.jp から SALON GUIDE へのリンク |
| 掲載店公式 | Reyel 等の Instagram・公式サイト「メディア掲載」から記事URL |
| Resta グループ | 関連サロンのブログ・採用ページから（自然な文脈で） |
| 地域メディア | 横浜・戸塚の地域情報サイトへの掲載依頼 |

### Hot Pepper 連携

- 各店 HPB ページの口コミ数・評価が検索にも効く
- 記事から HPB `/kr/` リンクで送客 → 口コミ増 → 店舗 MEO 向上の好循環
- 店舗スタッフに「SALON GUIDE 掲載」を店内POP・SNSで告知

### SNS 拡散文案テンプレ

**Instagram（店舗用）**
```
【メディア掲載のお知らせ】
横浜・戸塚エリアのネイルサロン5選に選ばれました✨
ジェル・フィルイン・定額ネイルの比較記事はこちら👇
https://salonlp.beagent.co.jp/press/areas/totsuka-nail-5.html
#戸塚ネイル #横浜ネイル #ジェルネイル #フィルイン
```

**LINE（Beagent / 店舗）**
```
戸塚でネイルサロンを探している方へ。
Reyelほか人気5店をネイルライターが比較した完全ガイドを公開しました。
▶ https://salonlp.beagent.co.jp/press/areas/totsuka-nail-5.html
```

### Google Business Profile（MEO）

- **各店舗**の GBP は店舗オーナーが管理
- 記事URLを「投稿」機能で週1回シェア
- カテゴリ「ネイルサロン」、サービスにジェル・フィルイン・パラジェルを明記
- 口コミ返信にキーワード（戸塚、ジェルネイル等）を自然に含める

---

## 4. コンテンツ拡張（中長期）

追加記事でロングテールキーワードを獲得：

| 記事案 | 狙うキーワード |
|--------|----------------|
| 戸塚駅前 ネイルサロン | 戸塚駅 ネイル |
| 中田 ネイルサロン | 中田駅 ジェルネイル |
| サクラス戸塚 ネイル | サクラス ネイル |
| 戸塚 フィルイン おすすめ | フィルイン 横浜 |
| 戸塚 パラジェル | パラジェル 戸塚 |

→ 各記事から `totsuka-nail-5.html` へ内部リンク

---

## 5. 計測 KPI

| 指標 | ツール |
|------|--------|
| 検索表示・クリック | Search Console |
| 流入キーワード | Search Console → 検索パフォーマンス |
| HPB 送客 | HPB 管理画面（店舗側） |
| 被リンク数 | Search Console → リンク |

**目標例（3ヶ月）**
- 「戸塚 ネイルサロン」で 10 位以内
- 月間オーガニッククリック 100+（記事単体）

---

## 6. 注意事項

- canonical は **salonlp.beagent.co.jp** を正とする（GitHub Pages は開発用）
- 掲載料受領の開示は記事内 disclaimer で対応済み
- 価格・メニューは HPB 最新情報と定期照合

---

## 関連ファイル

- サイトマップ: `/sitemap.xml`
- robots: `/robots.txt`
- 戸塚記事: `/press/areas/totsuka-nail-5.html`
- 掲載店向け: `/press/for-salons.html`
