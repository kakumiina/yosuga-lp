# LP Generator Project

## このプロジェクトについて
日本市場向け高CVランディングページを生成するプロジェクト。
PASONAの法則に基づく縦長構成、日本語フォント、複数CTAを標準装備。

## LP制作フロー

LP作成を依頼されたら、必ず以下の手順で進める：

### 1. スキルファイルを読む
```
skills/japanese-lp/SKILL.md        # 概要・クイックリファレンス
skills/japanese-lp/references/
  ├── structure.md                 # PASONAの法則・構成パターン
  ├── components.md                # 必須コンポーネント仕様
  └── design-rules.md              # フォント・カラー・レイアウト
```

### 2. 要件を確認
- ターゲット（誰に向けたLP？）
- ゴール（何をしてもらいたい？）
- 実績データ（数字で語れるもの）
- 業種（BtoB/BtoC/高額商材）

### 3. 生成・出力
- `output/` フォルダにHTMLを保存
- ファイル名: `{プロジェクト名}_lp.html`

## 絶対に避けること（AI slop）

- シリコンバレー的ミニマルデザイン
- 情報量の少ない「おしゃれ」なページ
- CTAボタン1箇所のみ
- 抽象的なキャッチコピー
- Inter、Roboto等の欧文フォント中心

## 必ず実現すること

- 縦長のセールスレター型構成
- 3秒で価値が伝わるファーストビュー
- 複数のCTAボタン配置（最低3箇所）
- 具体的な数字を使った実績訴求
- 日本語Webフォント（Noto Sans JP）

## 出力形式

### HTML + Tailwind CSS（推奨）
```html
<!-- Tailwind CDN -->
<script src="https://cdn.tailwindcss.com"></script>

<!-- Google Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@400;500;700;900&display=swap" rel="stylesheet">
```

### 必須セクション（省略禁止）
1. ファーストビュー（キャッチ + ビジュアル + CTA + 実績バッジ）
2. お悩み共感セクション
3. 選ばれる3つの理由
4. お客様の声（写真 + 具体的成果）
5. 料金プラン
6. よくある質問（FAQ）
7. 限定オファー + 最終CTA

## クイックコマンド

```
# サンプルLP生成
「テスト用のサンプルLP作って」

# クライアント向けLP生成
「{会社名}の{サービス}向けLP作って。ターゲットは{誰}、ゴールは{何}」
```
