# すまいPLUS

GitHub Pages で公開中のページ一覧です。

🌐 **トップページ（一覧）**: https://yutorin-ino.github.io/Create-repository/

---

## 公開ページ

### ランディングページ

| ページ名 | URL |
|---|---|
| すまいPLUS 賃貸情報サービス LP | https://yutorin-ino.github.io/Create-repository/sumai-plus-lp/ |
| すまいPLUS 賃貸情報サービス LP（画像付） | https://yutorin-ino.github.io/sumai-plus/ |

### プロモーション動画スライドショー

| ページ名 | URL |
|---|---|
| プロモスライドショー（通常版） | https://yutorin-ino.github.io/Create-repository/promo/promo.html |
| プロモスライドショー（暖色版） | https://yutorin-ino.github.io/Create-repository/promo/promo_warm.html |
| プロモスライドショー（暖色・白文字版） | https://yutorin-ino.github.io/Create-repository/promo/promo_warm_white.html |
| プロモスライドショー（人物入り版） | https://yutorin-ino.github.io/Create-repository/promo/promo_warm_white_person.html |
| プロモスライドショー（スマホ横向き版） | https://yutorin-ino.github.io/Create-repository/promo/promo_warm_white_person_sp.html |

### tolviviov — スマートホームセキュリティ

| ページ名 | URL |
|---|---|
| ランディングページ | https://yutorin-ino.github.io/Create-repository/tolviviov/tolviviov_lp.html |
| 広告プレビュー（全フォーマット） | https://yutorin-ino.github.io/Create-repository/tolviviov/tolviviov_ad_preview.html |
| Instagram / TikTok 広告（縦型 9:16） | https://yutorin-ino.github.io/Create-repository/tolviviov/ad_instagram_tiktok.html |
| X / YouTube 広告（横型 16:9） | https://yutorin-ino.github.io/Create-repository/tolviviov/ad_x_youtube.html |

---

## Sumai＋ 住宅リフォームHP（新規制作）

### コンセプト
**「リフォームを、もっと相談しやすく。」**

- ターゲット：30〜60代の住宅所有者・リフォーム初心者
- ブランドイメージ：親しみやすい・誠実・押し売りしない・地域密着
- カラー：ホワイトベース / ネイビー `#1a2d5a` / ベージュゴールド `#c8a96e`
- フォント：Noto Sans JP / Noto Serif JP（Google Fonts）
- レスポンシブ対応（スマホファースト）

### ファイル構成

```
sumai-plus/
├── index.html         # トップページ（メインHP）
├── promo.html         # プロモーションLP
└── images/
    ├── family.png     # FVメインビジュアル（家族）
    ├── staff.png      # スタッフ・代表写真
    ├── living.png     # リビング施工事例
    ├── kitchen.png    # キッチン施工事例
    ├── bathroom.png   # 浴室・洗面施工事例
    ├── exterior.png   # 外壁・外構施工事例
    └── customer.png   # お客様の声アバター
```

### ページ構成（index.html トップページ）

| セクション | 内容 |
|---|---|
| ① ファーストビュー | キャッチコピー・家族写真・CTA（無料相談 / LINE） |
| ② 実績バー | 累計施工1,200件・創業15年・満足度98%・相談無料 |
| ③ 選ばれる理由 | わかりやすい見積もり・無理な営業なし・健康提案・地域密着 |
| ④ 対応リフォーム | キッチン・浴室・トイレ・洗面・内装・外壁・リノベ |
| ⑤ 施工事例 | Before/After形式・費用・工期・お客様の声 |
| ⑥ 空気まで考える住まい | 断熱・換気・空気環境・省エネ |
| ⑦ お客様の声 | 星評価・写真付きレビュー |
| ⑧ ご相談の流れ | 6ステップ（問い合わせ〜アフターフォロー） |
| ⑨ 代表メッセージ | 井ノ口裕之・誠実で親しみやすいトーン |
| ⑩ お問い合わせ | LINE / 無料相談 / 電話 の3導線 |
| ⑪ フッター | 会社概要・営業時間・対応エリア・SNS |

### ページ構成（promo.html プロモーションLP）

| セクション | 内容 |
|---|---|
| ① ヒーロー | スタッフ写真・「その住まいの悩み、そのままにしていませんか？」 |
| ② ギャラリー | リビング・キッチン・浴室・外壁の施工写真グリッド |
| ③ お悩み | 6つの課題（水回り・使い勝手・断熱・費用・業者・バリアフリー） |
| ④ 選ばれる理由 | 地域密着・わかりやすい見積もり・スピーディ対応 |
| ⑤ ご利用の流れ | 5ステップ |
| ⑥ お客様の声 | 写真アバター付きレビュー |
| ⑦ お問い合わせ | LINE / フォーム / 電話 |

### スマホ対応
- 画面下部に固定フローティングCTA（LINE相談 / 無料相談 / 電話）
- ハンバーガーメニュー
- 電話番号タップ発信（`tel:` リンク）
- スクロールフェードインアニメーション

---

## ローカル確認

```bash
npx serve -l 8000
```

http://127.0.0.1:8000 を開いてください。
