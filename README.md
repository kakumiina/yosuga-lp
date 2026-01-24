# 🇯🇵 Japanese LP Generator

日本市場向け高コンバージョンランディングページを生成するClaude Code用スキル。

## 特徴

- **PASONAの法則**に基づく縦長構成
- **日本語Webフォント**（Noto Sans JP）標準
- **複数CTA配置**（最低3箇所）
- **信頼バッジ**（ゴールド系実績表示）
- **レスポンシブ対応**（モバイルファースト）

## 使い方

### Claude Code で使う

```bash
# リポジトリをクローン
git clone https://github.com/YOUR_USERNAME/lp-generator.git
cd lp-generator

# Claude Code 起動
claude
```

Claude Code内で依頼：
```
miinAIのAIコンサル向けLP作って。
ターゲット：中小企業経営者
ゴール：無料相談申込み
実績：導入50社、満足度95%
```

### フォルダ構成

```
lp-generator/
├── CLAUDE.md                    # Claude Code用指示書
├── README.md
├── skills/
│   └── japanese-lp/
│       ├── SKILL.md             # スキル概要
│       ├── references/
│       │   ├── structure.md     # PASONAの法則・構成
│       │   ├── components.md    # コンポーネント仕様
│       │   └── design-rules.md  # デザインルール
│       └── assets/
│           └── template.html    # ベーステンプレート
└── output/                      # 生成物の出力先
```

## スキルの内容

### structure.md
- PASONAの法則（Problem → Affinity → Solution → Offer → Narrowing → Action）
- セクション配置順序
- 業種別カスタマイズ（BtoB/BtoC/高額商材）

### components.md
- ファーストビュー
- 実績バッジ
- お悩み共感セクション
- 選ばれる3つの理由
- お客様の声
- 料金プラン
- FAQ
- CTAボタン
- 限定オファー

### design-rules.md
- フォント設定（Noto Sans JP）
- 業種別カラーパレット
- CTAボタン色（オレンジ/緑/赤）
- レイアウト・余白
- レスポンシブ設定
- Tailwind CSS設定例

## 絶対に避けること（AI slop）

❌ シリコンバレー的ミニマルデザイン  
❌ 情報量の少ない「おしゃれ」なページ  
❌ CTAボタン1箇所のみ  
❌ 抽象的なキャッチコピー  
❌ 欧文フォント中心のデザイン

## ライセンス

MIT

## 作成者

miinAI - AIで人の愛・幸福・時間を増やす
