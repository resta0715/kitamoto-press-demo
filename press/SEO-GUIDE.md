# SALON GUIDE — SEO・集客拡大ガイド

Beagent 編集部 · 2026年6月

本ガイドは `salonlp.beagent.co.jp` の主要記事（北本髪質改善7選・戸塚ネイル5選）および SALON GUIDE 全体の検索流入・認知拡大のための実践手順です。

---

## 1. 今週中にやること（優先度：高）

### Google Search Console

1. [Google Search Console](https://search.google.com/search-console) に `salonlp.beagent.co.jp` を登録
2. DNS または HTML ファイルで所有権確認
3. **サイトマップ送信**: `https://salonlp.beagent.co.jp/sitemap.xml`
4. 「URL 検査」で主要記事を登録・インデックス登録をリクエスト  
   - `https://salonlp.beagent.co.jp/press/kitamoto-kounosu-okegawa-7salons.html`
   - `https://salonlp.beagent.co.jp/press/areas/totsuka-nail-5.html`

### Xserver 再アップロード

- 最新 `salonlp-beagent.zip` を docroot 直下に解凍（二重フォルダにしない）
- ルートに `sitemap.xml` / `robots.txt`、press 配下に記事・画像があることを確認
- 古い `.htaccess` は削除（sitemap/robots が 500 になる原因になりやすい）

### 記事URLの拡散（SNS・LINE）

掲載サロン・Beagent 公式から同一 URL を共有：

```
https://salonlp.beagent.co.jp/press/kitamoto-kounosu-okegawa-7salons.html
https://salonlp.beagent.co.jp/press/areas/totsuka-nail-5.html
```

---

## 2. オンページ SEO（実装済み）

### 北本・鴻巣・桶川 髪質改善7選

| 項目 | 内容 |
|------|------|
| URL | `/press/kitamoto-kounosu-okegawa-7salons.html` |
| title / description | 北本 髪質改善 美容室、鴻巣、桶川、Resta、React 等 |
| canonical | `https://salonlp.beagent.co.jp/press/kitamoto-kounosu-okegawa-7salons.html` |
| OGP / Twitter Card | resta-interior.png |
| JSON-LD | Article, ItemList, FAQPage, BreadcrumbList, BeautySalon×7 |
| FAQ | 5問（北本人気店／Resta vs React／鴻巣桶川／相場／縮毛矯正） |
| 内部リンク | ハブ・戸塚ネイル・for-salons |

**狙うキーワード例:** 北本 髪質改善、北本 美容室、鴻巣 美容室、桶川 縮毛矯正、Resta 北本、React 北本

### 横浜・戸塚 ネイル5選

| 項目 | 内容 |
|------|------|
| URL | `/press/areas/totsuka-nail-5.html` |
| title / description | **戸塚 ネイルサロン**を先頭KWに配置。戸塚駅・中田・ジェル・フィルイン |
| canonical | `https://salonlp.beagent.co.jp/press/areas/totsuka-nail-5.html` |
| OGP / Twitter Card | hero-nail.jpg |
| JSON-LD | Article, ItemList, FAQPage, BreadcrumbList, BeautySalon×5 |
| FAQ | 5問（おすすめ／安い／フィルイン／ジェル相場／中田・サクラス） |
| 内部リンク | ハブ「戸塚ネイルサロン特集」・北本7選・for-salons |

**狙うキーワード（優先順）:** 戸塚 ネイルサロン → 戸塚 ネイル → 戸塚駅 ネイル → 横浜 戸塚 ネイルサロン → 戸塚 ジェルネイル → 中田 ネイルサロン → 戸塚 ネイル おすすめ → 戸塚 ネイル 安い → 戸塚 フィルイン

---

## 2b. 「戸塚 ネイルサロン」で上位を取るための施策

### Search Console クエリ監視

1. GSC → **検索パフォーマンス** → クエリフィルタに `戸塚` を入力
2. 週次で確認する指標：
   - **表示回数・CTR** — 「戸塚 ネイルサロン」「戸塚 ネイル」の順位変動
   - **平均掲載順位** — 目標：3ヶ月で 10 位以内
3. インデックス登録：URL 検査 → `totsuka-nail-5.html` → **インデックス登録をリクエスト**（更新のたび）
4. クリックが付かないクエリ（表示のみ）→ 記事の FAQ / H2 に自然追加を検討

### 被リンクのアンカーテキスト

被リンク獲得時は、可能な限りアンカーに **「戸塚 ネイルサロン」** を含める：

| リンク元 | 推奨アンカー | URL |
|----------|-------------|-----|
| Reyel 公式・Instagram | 戸塚 ネイルサロンおすすめ記事 | totsuka-nail-5.html |
| Beagent 本体 | 戸塚ネイルサロン特集（SALON GUIDE） | totsuka-nail-5.html |
| 地域ブログ・掲示板 | 戸塚のネイルサロン比較ガイド | totsuka-nail-5.html |
| HPB 店舗ブログ | メディア掲載：戸塚 ネイルサロン5選 | totsuka-nail-5.html |

**避けるべきアンカー:** 「こちら」「詳細」「click here」だけのリンク

### 店舗側に依頼する拡散文（アンカー付き）

```
SALON GUIDEに「戸塚 ネイルサロンおすすめ5選」として掲載されました。
▶ https://salonlp.beagent.co.jp/press/areas/totsuka-nail-5.html
#戸塚ネイルサロン #戸塚ネイル #横浜ネイル
```

### sitemap 優先度

- `totsuka-nail-5.html` → **priority 1.0**（メイン集客記事）
- 更新のたび `lastmod` を更新し GSC で再送信

---

## 3. オフページ SEO・拡大施策

### 被リンク（リンク獲得）

| 施策 | 具体 |
|------|------|
| Beagent 本体 | beagent.co.jp から SALON GUIDE へのリンク |
| Resta / React グループ | 北本・鴻巣・桶川店の Instagram・採用ページから記事URL |
| Reyel 等ネイル店 | 公式SNS「メディア掲載」から戸塚記事URL |
| 地域メディア | 埼玉北部・横浜戸塚の地域情報サイトへの掲載依頼 |

### Hot Pepper 連携

- 各店 HPB ページの口コミ数・評価が検索にも効く
- 記事から HPB `/kr/` リンクで送客 → 口コミ増 → 店舗 MEO 向上の好循環
- 店舗スタッフに「SALON GUIDE 掲載」を店内POP・SNSで告知

### SNS 拡散文案テンプレ

**Instagram（Resta / React 用）**
```
【メディア掲載のお知らせ】
北本・鴻巣・桶川の髪質改善美容室7選に選ばれました✨
Resta・Reactほか人気サロン比較記事はこちら👇
https://salonlp.beagent.co.jp/press/kitamoto-kounosu-okegawa-7salons.html
#北本美容室 #髪質改善 #Resta #React #埼玉美容室
```

**Instagram（Reyel 等ネイル店用）**
```
【メディア掲載のお知らせ】
横浜・戸塚エリアのネイルサロン5選に選ばれました✨
https://salonlp.beagent.co.jp/press/areas/totsuka-nail-5.html
#戸塚ネイル #横浜ネイル #ジェルネイル
```

### Google Business Profile（MEO）

- **各店舗**の GBP は店舗オーナーが管理
- 記事URLを「投稿」機能で週1回シェア
- カテゴリ・サービスに髪質改善／ジェルネイル等を明記
- 口コミ返信に地域キーワードを自然に含める

---

## 4. コンテンツ拡張（中長期）

| 記事案 | 狙うキーワード |
|--------|----------------|
| 北本駅 美容室 髪質改善 | 北本駅 美容室 |
| 鴻巣 縮毛矯正 | 鴻巣 髪質改善 |
| 桶川 美容室 | 桶川 カラー |
| 戸塚駅前 ネイルサロン | 戸塚駅 ネイル |
| 中田 ネイルサロン | 中田駅 ジェルネイル |

→ 各記事から既存ハブ記事へ内部リンク

---

## 5. 計測 KPI

| 指標 | ツール |
|------|--------|
| 検索表示・クリック | Search Console |
| 流入キーワード | Search Console → 検索パフォーマンス |
| HPB 送客 | HPB 管理画面（店舗側） |
| 被リンク数 | Search Console → リンク |

**目標例（3ヶ月）**
- 「北本 髪質改善」「戸塚 ネイルサロン」で 10 位以内
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
- 北本7選: `/press/kitamoto-kounosu-okegawa-7salons.html`
- 戸塚ネイル: `/press/areas/totsuka-nail-5.html`
- 掲載店向け: `/press/for-salons.html`
