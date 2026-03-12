<div align="center">

# 🎨 Awesome AI 画像生成

### 2026年 AI 画像モデル完全ガイド

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Models](https://img.shields.io/badge/画像モデル-46-blue.svg)](https://www.atlascloud.ai?ref=JPM683)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/atlascloud/awesome-ai-image-generation?style=social)](https://github.com/atlascloud/awesome-ai-image-generation)

**AI画像生成モデル・プロンプト・ツール・リソースの厳選コレクション**

**Google Nano Banana 2 · Imagen4 · ByteDance Seedream · Flux · Wan · Qwen-Image** など主要モデルを網羅。

[English](README.md) · [简体中文](README_zh-CN.md) · [日本語](README_ja.md) · [한국어](README_ko.md)

---

**⭐ 役に立ったら Star をお願いします — 他の方にも届きます！**

</div>

---

## 🚀 スポンサー — 46画像モデル、1つのAPI

<div align="center">

**[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)** — 全主要AI画像モデルの統一API。

1つのAPIキー。46の画像モデル。Google、ByteDance、Black Forest Labs、Alibaba — すべて一か所に。

🎁 **初回チャージで25%ボーナス（最大$100）**

[![Atlas Cloudを試す](https://img.shields.io/badge/Atlas_Cloud-無料クレジット-blue?style=for-the-badge)](https://www.atlascloud.ai?ref=JPM683)

> 🔒 **エンタープライズグレードのセキュリティ** — Atlas Cloud は **SOC I & II 認証取得** | **HIPAA 準拠** | 米国企業、99.9% 稼働率 SLA。

</div>

---

## 📑 目次

- [2026年 AI画像モデル全体像](#-2026年-ai画像モデル全体像)
- [Googleモデル](#-googleモデル)
  - [Nano Banana 2](#nano-banana-2)
  - [Imagen4ファミリー](#imagen4ファミリー)
- [ByteDance Seedream](#-bytedance-seedream)
  - [Seedream v5.0 Lite](#seedream-v50-lite)
  - [Seedream v4.5 / v4](#seedream-v45--v4)
- [Black Forest Labs — Flux](#-black-forest-labs--flux)
  - [Flux Dev & Schnell](#flux-dev--schnell)
  - [Flux LoRA](#flux-lora)
  - [Flux Kontext](#flux-kontext)
- [Alibabaモデル](#-alibabaモデル)
  - [Wan 2.6 / 2.5](#wan-26--25)
  - [Qwen-Image](#qwen-image)
  - [Z-Image Turbo](#z-image-turbo)
- [ユースケース別推奨](#-ユースケース別推奨)
- [クイックスタート — 統一API](#-クイックスタート--統一api)
- [プロンプトエンジニアリングガイド](#-プロンプトエンジニアリングガイド)
- [プロンプトコレクション（50+）](#-プロンプトコレクション50)
- [ツール＆エコシステム](#-ツールエコシステム)
- [料金詳細](#-料金詳細)
- [よくある質問](#-よくある質問)
- [Star履歴](#-star履歴)
- [コントリビュート](#-コントリビュート)
- [ライセンス](#-ライセンス)

---

## 📊 2026年 AI画像モデル全体像

> 2026年にAPIで利用可能な全主要AI画像モデルの包括的比較。

| モデル | プロバイダー | タイプ | 最大解像度 | 速度 | 編集 | LoRA | バッチ | API価格 |
|:------|:------------|:------|:----------|:-----|:-----|:-----|:------|:--------|
| **Nano Banana 2** | Google | T2I/編集 | 4K | ⚡⚡⚡ | ✅ | ❌ | ❌ | $0.072/枚から |
| **Nano Banana 2 Dev** | Google | T2I/編集 | 4K | ⚡⚡⚡ | ✅ | ❌ | ❌ | $0.072/枚から |
| **Nano Banana Pro** | Google | T2I/編集 | 4K | ⚡⚡ | ✅ | ❌ | ❌ | 変動 |
| **Nano Banana** | Google | T2I/編集 | 2K | ⚡⚡ | ✅ | ❌ | ❌ | 変動 |
| **Imagen4 Ultra** | Google | T2I | 4K | ⚡ | ❌ | ❌ | ❌ | 高め |
| **Imagen4** | Google | T2I | 4K | ⚡⚡ | ❌ | ❌ | ❌ | 変動 |
| **Imagen4 Fast** | Google | T2I | 2K | ⚡⚡⚡ | ❌ | ❌ | ❌ | 変動 |
| **Imagen3** | Google | T2I | 2K | ⚡⚡ | ❌ | ❌ | ❌ | 変動 |
| **Imagen3 Fast** | Google | T2I | 2K | ⚡⚡⚡ | ❌ | ❌ | ❌ | 変動 |
| **Seedream v5.0 Lite** | ByteDance | T2I/編集 | 2K | ⚡⚡ | ✅ | ❌ | ✅ 15枚 | 変動 |
| **Seedream v4.5** | ByteDance | T2I/編集 | 2K | ⚡⚡ | ✅ | ❌ | ✅ 15枚 | 変動 |
| **Seedream v4** | ByteDance | T2I/編集 | 2K | ⚡⚡ | ✅ | ❌ | ✅ 15枚 | 変動 |
| **Flux Dev** | BFL | T2I | 2K | ⚡⚡ | ❌ | ✅ | ❌ | 変動 |
| **Flux Schnell** | BFL | T2I | 1K | ⚡⚡⚡ | ❌ | ❌ | ❌ | 最安 |
| **Flux Dev LoRA** | BFL | T2I | 2K | ⚡⚡ | ❌ | ✅ | ❌ | 変動 |
| **Flux Kontext Dev** | BFL | 編集 | 2K | ⚡⚡ | ✅ | ❌ | ❌ | 変動 |
| **Flux Kontext Dev LoRA** | BFL | 編集 | 2K | ⚡⚡ | ✅ | ✅ | ❌ | 変動 |
| **Wan 2.6 T2I** | Alibaba | T2I | 2K | ⚡⚡ | ❌ | ❌ | ❌ | 変動 |
| **Wan 2.6 Edit** | Alibaba | 編集 | 2K | ⚡⚡ | ✅ | ❌ | ❌ | 変動 |
| **Wan 2.5 T2I** | Alibaba | T2I | 2K | ⚡⚡ | ❌ | ❌ | ❌ | 変動 |
| **Wan 2.5 Edit** | Alibaba | 編集 | 2K | ⚡⚡ | ✅ | ❌ | ❌ | 変動 |
| **Qwen-Image Max** | Alibaba | T2I | 2K | ⚡⚡ | ❌ | ❌ | ❌ | 変動 |
| **Qwen-Image Plus** | Alibaba | T2I | 2K | ⚡⚡ | ❌ | ❌ | ❌ | 変動 |
| **Qwen-Image Edit** | Alibaba | 編集 | 2K | ⚡⚡ | ✅ | ❌ | ❌ | 変動 |
| **Qwen-Image Edit Plus** | Alibaba | 編集 | 2K | ⚡⚡ | ✅ | ❌ | ❌ | 変動 |
| **Z-Image Turbo** | Alibaba | T2I | 2K | ⚡⚡⚡ | ❌ | ❌ | ❌ | 変動 |

> 💡 **全46モデルを1つのAPIで利用可能** — [Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)

---

## 🔷 Googleモデル

### Nano Banana 2

> **Googleの最新・最速画像生成モデル（2026年）。** 超高速推論でフォトリアルな画像を生成、最大14枚の参照画像による編集、優れたテキストレンダリング機能。

**主な特徴：**
- 🏎️ **最速の生成** — ほとんどのプロンプトで1秒以下の推論
- 🎯 **14枚の参照画像** — 業界最高の画像編集・スタイル転送
- ✍️ **テキストレンダリング** — 生成画像内の正確な文字配置
- 🖼️ **4K出力** — 超高解像度
- 💰 **$0.072/枚から** — プレミアムモデルの中で最もコスパが良い

**バリエーション：**
| バリエーション | 最適な用途 | 編集 | 速度 |
|:-------------|:----------|:-----|:-----|
| Nano Banana 2 T2I | テキストから画像生成 | ❌ | ⚡⚡⚡ |
| Nano Banana 2 Edit | 画像編集 | ✅（14枚参照） | ⚡⚡⚡ |
| Nano Banana 2 Developer T2I | 開発/テスト | ❌ | ⚡⚡⚡ |
| Nano Banana 2 Developer Edit | 開発/テスト | ✅ | ⚡⚡⚡ |

**Nano Banana 2 プロンプト例：**

```
1. そばかすのある若い女性のハイパーリアリスティックなポートレート、
   ゴールデンアワーの日差しが赤褐色の髪を透過、浅い被写界深度、
   Hasselblad X2D撮影、100mm f/1.4

2. 真夜中の生物発光ビーチの空撮、電気ブルーに輝く波、暗い火山砂、
   潮だまりに映る星、National Geographic品質

3. スチームパンクなカフェの内装、壁に真鍮のパイプと歯車、銅製
   エスプレッソマシンから立ち上る蒸気、温かいアンバーの照明、
   ヴィンテージレザーチェア、超精細4Kレンダリング

4. 商品撮影：大理石の上の高級香水ボトル、プリズム光を捕らえる
   水滴、ダークムーディーな背景、商業広告品質、8K解像度

5. タイポグラフィデザイン：「FUTURE」のクロム液体メタル文字が
   ネオンの都市風景の上に浮遊、濡れた路面の反射、サイバーパンク
   美学、シネマティック照明
```

### Imagen4ファミリー

> **Googleのフラッグシップ画像生成スイート。** 品質/速度のトレードオフに応じた3つのティア。

| モデル | 品質 | 速度 | 最適な用途 |
|:------|:-----|:-----|:----------|
| **Imagen4 Ultra** | ⭐⭐⭐⭐⭐ | ⚡ | 最高品質、ファインアート、印刷 |
| **Imagen4** | ⭐⭐⭐⭐ | ⚡⚡ | 品質と速度のバランス |
| **Imagen4 Fast** | ⭐⭐⭐ | ⚡⚡⚡ | ラピッドプロトタイピング |

**Imagen4 Ultra プロンプト例：**

```
1. ルネサンス風の油絵で描かれた現代都市の夕暮れ、ドラマチックな
   キアロスクーロ照明、見える筆致、金箔アクセント、美術館品質

2. 蝶の翅の極端なマクロ写真、虹色の鱗粉が虹色に反射、露の滴が
   小さなレンズに、フォーカスステッキング、Nikon Z9 + 105mmマクロ

3. SF映画のシネマティックスチル：異星の結晶渓谷の縁に立つ孤独な
   宇宙飛行士、ツインサンセット、ボリュメトリックフォグ、IMAX品質

4. 超精細な建築ビジュアライゼーション：未来主義的な日本の寺院、
   伝統的な木組みとパラメトリックデザインの融合、桜、朝霧

5. フォトリアルな静物画：真鍮の望遠鏡、アストロラーベ、コンパス、
   古地図 — マホガニーの机の上、キャンドルライト、フェルメール
   風照明、8K超精細
```

---

## 🟢 ByteDance Seedream

### Seedream v5.0 Lite

> **ByteDanceの最新画像モデル（2026年）。** プロンプト追従性の向上、人体解剖学の改善、1リクエストで最大15枚のバッチ生成。

**主な特徴：**
- 📦 **バッチ15枚** — 1回のAPIコールで最大15バリエーション
- ✏️ **編集+シーケンシャル** — 高度な編集とシーケンシャル処理
- 🎨 **中国語・英語対応** — バイリンガルプロンプトサポート
- ⚡ **高速推論** — 大量生成に最適化

### Seedream v4.5 / v4

**Seedream v5.0 vs v4.5 比較：**

| 機能 | v5.0 Lite | v4.5 | v4 |
|:-----|:----------|:-----|:---|
| プロンプト追従 | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ |
| 人体解剖学 | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ |
| テキストレンダリング | ⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ |
| 速度 | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| バッチ（シーケンシャル） | ✅ 15枚 | ✅ 15枚 | ✅ 15枚 |
| 編集 | ✅ | ✅ | ✅ |

**Seedream v5.0 プロンプト例：**

```
1. 鮮やかなデジタルカラーで再解釈された中国水墨画、霧に包まれた
   山々、流れ落ちる滝、橋の上の孤高の学者、伝統的構図にモダンな
   色彩パレット

2. 超リアルなフード写真：とんこつラーメン一杯、立ち上る湯気、
   完璧な半熟卵、チャーシュー、のり、ネギ、45度アングル撮影

3. 2050年の未来的な上海スカイライン、有機的形状の超高層ビル間を
   飛行する乗り物、ホログラフィック広告、紫とオレンジの雲の夕焼け

4. ファッションエディトリアル：無限鏡の部屋に立つ前衛的幾何学
   デザインの服を着たモデル、草間彌生インスパイア、ドラマチックな
   スタジオ照明、Vogue誌品質

5. 魔法の図書館、無限に浮遊する本棚が空に螺旋状に伸びる、金色の
   塵の粒子、光るルーン文字の古書、温かいキャンドルライト
```

**シーケンシャルモード（バッチ生成）の活用：**
- 商品バリエーション生成（色、角度）
- ストーリーボードシーケンス作成
- A/Bテスト用の構図比較
- SNSコンテンツの一括制作

---

## ⬛ Black Forest Labs — Flux

### Flux Dev & Schnell

> **オープンソースの強力モデル群。** Fluxは AI画像生成コミュニティの基盤となり、比類なきLoRAエコシステムを持つ。

| モデル | 速度 | 品質 | 最適な用途 |
|:------|:-----|:-----|:----------|
| **Flux Dev** | ⚡⚡ | ⭐⭐⭐⭐ | 本番環境、品質重視 |
| **Flux Schnell** | ⚡⚡⚡ | ⭐⭐⭐ | 最速、最安、プロトタイピング |

**Flux Dev** の強み：
- 🎭 **コミュニティLoRA** — 数千のコミュニティ学習済みスタイル
- 🔓 **Atlas Cloudで検閲なし** — 完全な創作の自由
- 🎨 **優れた構図力** — 空間関係の強い理解力
- 📝 **テキストレンダリング** — オープンモデルの中で優秀

### Flux LoRA

> **カスタムスタイル生成** — コミュニティ学習LoRAモデルを活用。

人気LoRAソース：
- [Civitai](https://civitai.com) — 最大のLoRAリポジトリ
- [HuggingFace](https://huggingface.co) — オープンモデルハブ

### Flux Kontext

> **コンテキスト内画像編集** — テキスト指示で既存画像を編集。

**Flux プロンプト例：**

```
1. [Flux Dev] 二重露光写真：オオカミの顔と北方の松林が融合、
   月光、神秘的な雰囲気、ファインアート写真、モノクロに微かな
   ブルートーン

2. [Flux Dev] アイソメトリック3Dレンダリング：居心地の良いミニ
   アパート、小さなランプの温かい光、窓辺の植物、ソファで眠る猫、
   ボクセルアートスタイル、ティルトシフト効果、パステルカラー

3. [Flux Schnell] クイックコンセプトスケッチ：ロボットバリスタが
   ラテアートを作る、スチームパンクカフェ、暖色、イラストスタイル

4. [Flux Kontext] 画像編集：背景を熱帯ビーチの夕焼けに変更、
   被写体はそのまま維持、自然な照明の一貫性を保つ

5. [Flux Dev LoRA] スタジオジブリ風：野の花に覆われた魔法の浮島、
   古代の石の遺跡、赤い傘を持つ少女が端に立つ、足元に雲、
   温かい午後の光
```

---

## 🟡 Alibabaモデル

### Wan 2.6 / 2.5

> **Alibabaのマルチモーダルモデル。** 動画生成で有名だが、画像生成と編集も優秀。

| モデル | タイプ | 強み |
|:------|:------|:-----|
| **Wan 2.6 T2I** | テキスト→画像 | 最新品質、最高のプロンプト追従 |
| **Wan 2.6 Edit** | 画像編集 | 高度な編集機能 |
| **Wan 2.5 T2I** | テキスト→画像 | 実績あり、安定 |
| **Wan 2.5 Edit** | 画像編集 | 信頼性の高い編集 |

### Qwen-Image

> **AlibabaのQwen搭載画像生成ファミリー。** 中国語・英語バイリンガル対応。

| モデル | タイプ | 最適な用途 |
|:------|:------|:----------|
| **Qwen-Image Max** | T2I | 最高品質 |
| **Qwen-Image Plus** | T2I | バランス型 |
| **Qwen-Image Edit** | 編集 | 基本編集 |
| **Qwen-Image Edit Plus** | 編集 | 高度な編集 |

### Z-Image Turbo

> **速度重視モデル** — 低コストで高速生成。

**Alibabaモデル プロンプト例：**

```
1. [Wan 2.6] 秋の静かな禅庭園、砂紋、苔むした石、石の水盤に
   浮かぶ一枚の赤いモミジの葉、竹林を通る柔らかい朝の光

2. [Qwen-Image Max] 華やかな春節の祝典、伝統的な龍舞、古い通りを
   飾る赤い提灯、塔の上に上がる花火、祝祭的な群衆

3. [Wan 2.6 Edit] 昼間の都市風景をサイバーパンクの夜景に変換、
   ネオンサイン、ホログラフィック看板、雨に濡れた反射する通り

4. [Qwen-Image Plus] 水彩画イラストのヨーロッパの村のマーケット、
   新鮮な農産物の屋台、石畳の通り、朝もや、温かい金色の光

5. [Z-Image Turbo] 商品撮影：クリーンな白い面のミニマルワイヤレス
   イヤホン、ソフトなスタジオ照明、わずかな反射、Apple風商品写真
```

---

## 🎯 ユースケース別推奨

| ユースケース | 推奨モデル | 理由 | 推定価格 |
|:------------|:----------|:-----|:---------|
| ⚡ 速度/プロトタイプ | **Flux Schnell** | 最速、1秒以下 | 最安 |
| 📷 フォトリアリズム | **Nano Banana 2** | 最もリアルな出力、4K | $0.072/枚から |
| 🏆 最高品質 | **Imagen4 Ultra** | 最高の細部表現 | 高め |
| 📦 バッチ生成 | **Seedream v5.0** | 1バッチ15枚 | 変動 |
| 🎨 カスタムスタイル | **Flux Dev LoRA** | 数千のコミュニティLoRA | 変動 |
| ✏️ 画像編集 | **Nano Banana 2 Edit** | 14枚の参照画像対応 | $0.072/枚から |
| 💰 予算重視 | **Flux Schnell** | 最低の画像単価 | 最安 |
| 🔓 検閲なし/NSFW | **Flux Dev**（Atlas） | コンテンツフィルターなし | 変動 |
| 📝 画像内テキスト | **Nano Banana 2** | 最高のテキスト精度 | $0.072/枚から |
| 🏢 エンタープライズ | **Imagen4** | Google品質、高信頼性 | 変動 |

---

## ⚡ クイックスタート — 統一API

> **1つのAPI、全46モデル。** モデル切り替えはパラメーター1つの変更だけ。

### cURL

```bash
# テキストから画像生成 — Nano Banana 2
curl -X POST "https://api.atlascloud.ai/v1/images/generations" \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "nano-banana-2",
    "prompt": "ハイパーリアルなポートレート、ゴールデンアワー照明、浅い被写界深度",
    "size": "1024x1024",
    "n": 1
  }'
```

### Python

```python
# Atlas Cloud統一APIで画像を生成
import requests

API_KEY = "YOUR_API_KEY"
BASE_URL = "https://api.atlascloud.ai/v1"

def generate_image(prompt, model="nano-banana-2", size="1024x1024"):
    """
    統一APIで画像を生成。
    全46モデル対応、modelパラメーターを変更するだけ。
    """
    response = requests.post(
        f"{BASE_URL}/images/generations",
        headers={
            "Authorization": f"Bearer {API_KEY}",
            "Content-Type": "application/json"
        },
        json={
            "model": model,
            "prompt": prompt,
            "size": size,
            "n": 1
        }
    )
    return response.json()

# 異なるモデルで生成 — modelパラメーターを変えるだけ
result_nb2 = generate_image(
    "壮大な山の夕焼け",
    model="nano-banana-2"        # Google最新モデル
)

result_flux = generate_image(
    "壮大な山の夕焼け",
    model="flux-dev"             # Fluxオープンソースモデル
)

result_seedream = generate_image(
    "壮大な山の夕焼け",
    model="seedream-v5-lite"     # ByteDance最新モデル
)

# 結果を出力
print(result_nb2)
```

### JavaScript / Node.js

```javascript
// Atlas Cloud統一APIで画像を生成
const API_KEY = "YOUR_API_KEY";
const BASE_URL = "https://api.atlascloud.ai/v1";

/**
 * 画像を生成 — 全46モデル対応
 * @param {string} prompt - 画像の説明
 * @param {string} model - モデル名
 * @param {string} size - 出力サイズ
 */
async function generateImage(prompt, model = "nano-banana-2", size = "1024x1024") {
  const response = await fetch(`${BASE_URL}/images/generations`, {
    method: "POST",
    headers: {
      "Authorization": `Bearer ${API_KEY}`,
      "Content-Type": "application/json"
    },
    body: JSON.stringify({
      model,
      prompt,
      size,
      n: 1
    })
  });
  return response.json();
}

// 使用例
(async () => {
  const result = await generateImage(
    "サイバーパンクの夜景都市、ネオンライト、雨",
    "nano-banana-2"
  );
  console.log("生成結果:", result);
})();
```

> 📖 完全なAPIドキュメント：[Atlas Cloud Docs](https://www.atlascloud.ai?ref=JPM683)

---

## 🧠 プロンプトエンジニアリングガイド

### 基本原則

優れたプロンプトの構造：

```
[被写体] + [スタイル/メディア] + [構図] + [照明] + [品質修飾子]
```

**1. 被写体 — 具体的に**
| 弱い ❌ | 強い ✅ |
|:-------|:-------|
| 女性 | ショートヘアの25歳東アジア人女性 |
| 都市 | 午前2時、雨に濡れた東京の路地 |
| 花 | 朝露のついた白い牡丹一輪 |

**2. スタイル・メディアキーワード**

| カテゴリ | キーワード |
|:--------|:---------|
| 写真 | 一眼レフ、フィルム写真、ポラロイド、空撮、マクロ、ティルトシフト |
| デジタル | コンセプトアート、デジタルペインティング、3Dレンダリング、CGI |
| 伝統芸術 | 油絵、水彩、墨絵、木炭、鉛筆スケッチ |
| イラスト | ベクターアート、フラットデザイン、アイソメトリック、線画 |
| 特定スタイル | ジブリ、アールヌーヴォー、バウハウス、ヴェイパーウェイブ |

**3. 構図テクニック**

| テクニック | 説明 | 例 |
|:----------|:-----|:---|
| 三分割法 | 被写体を中心からずらす | 「右三分の一に配置」 |
| リーディングライン | 視線を誘導する線 | 「地平線へ続く線路」 |
| シンメトリー | 左右対称の構図 | 「完全に対称な寺院の入口」 |
| フレーム内フレーム | 自然なフレーミング | 「石のアーチ越しに見る」 |
| 俯瞰 | 真上からの視点 | 「庭園の空中俯瞰ショット」 |

**4. 照明ボキャブラリー**

| 照明 | 効果 | 最適な用途 |
|:-----|:-----|:----------|
| ゴールデンアワー | 暖かく柔らかい光 | ポートレート、風景 |
| ブルーアワー | 冷たく幻想的 | 都市風景 |
| レンブラント照明 | 頬にドラマチックな三角形 | ポートレート |
| リムライティング | 輝くエッジ | シルエット |
| ボリュメトリック | 見える光の筋 | ファンタジー |
| キアロスクーロ | 強い明暗のコントラスト | ファインアート |
| ネオン照明 | カラフルな人工光 | サイバーパンク |

**5. 品質・解像度修飾子**

```
超精細、8K解像度、高精細、傑作品質、プロフェッショナル写真、
受賞作品、シャープフォーカス、精密なディテール、ボリュメトリック
レンダリング、レイトレーシング
```

### モデル別ヒント

**Nano Banana 2：**
- カメラ/レンズの仕様が効果的（例：「Sony A7R V、85mm f/1.2で撮影」）
- テキスト生成：目的のテキストを引用符で囲む
- 参照画像で一貫性が大幅に向上

**Seedream v5.0：**
- 中国語プロンプトをネイティブサポート
- シーケンシャルモード：番号付きリストでバリエーションを記述
- アジアの美学・文化的要素が得意

**Flux Dev：**
- 長く詳細なプロンプトでより良い結果
- LoRAのトリガーワードをプロンプトに含める必要がある
- キーワード列挙より自然言語が効果的

---

## 🎁 プロンプトコレクション（50+）

### 📷 フォトリアル

```
1. 日本の老漁師のハイパーリアルなクローズアップ、深い皺が数十年の
   海での物語を語る、白髪混じりの無精髭、風化した漁師帽、顔に
   ゴールデンアワーの光、海とボートのボケ背景、Canon EOS R5、
   135mm f/2、8K
   → 推奨：Nano Banana 2 | Imagen4 Ultra

2. 秋のノルウェーフィヨルドの空撮、エメラルドの水にオレンジと赤の
   山が映る、岸辺の小さな赤い小屋、水面上に漂う朝霧、DJI品質
   → 推奨：Imagen4 Ultra | Nano Banana 2

3. ソウルの雨の夜のストリート写真、濡れた路面に映るネオンサイン、
   透明な傘を持つ一人の人物、浅い被写界深度、Leica M11
   → 推奨：Nano Banana 2 | Flux Dev

4. 露に濡れたバラの花びらの上のハエトリグモのマクロ写真、虹色の
   鋏角、8つの目に映る撮影者、セタエの極端なディテール
   → 推奨：Imagen4 Ultra

5. 北欧ミニマリスト住宅のフォトリアルなインテリア、雪に覆われた
   森を望む床から天井までの窓、温かい木の色調、イームズラウンジ
   チェア、暖炉、ヒュッゲな雰囲気
   → 推奨：Nano Banana 2 | Seedream v5.0
```

### 🎨 デジタルアート

```
6. 廃墟の大聖堂を貫いて育つ巨大な古木、石柱に巻きつく根、ステンド
   グラスから差し込む色彩豊かな光、苔とシダに覆われた空間
   → 推奨：Flux Dev | Imagen4

7. サイバーパンクの侍が東京の屋上に立つ、刀にネオンの街灯が反射、
   サーボが見える機械の腕、ホログラフィックHUDバイザー、雨
   → 推奨：Flux Dev | Seedream v5.0

8. 生物発光建築の海底文明、クラゲ型の建物、魚群が交通、珊瑚に
   覆われた橋、深海ブルーのグラデーション、ゲームコンセプトアート
   → 推奨：Imagen4 Ultra | Flux Dev

9. 居心地の良い魔女の小屋、棚で泡立つ薬、呪文書の山の上の黒猫、
   天井から乾燥中のハーブ、暖炉の光、浮遊するキャンドル
   → 推奨：Flux Dev LoRA | Seedream v5.0

10. スチームパンクの飛行船ドッキングステーション、雲の上、真鍮と
    銅の建築、巨大プロペラ、ヴィクトリア朝の乗客
    → 推奨：Imagen4 Ultra | Flux Dev
```

### 📦 商品写真

```
11. 高級機械式腕時計が空中に浮遊、周囲に散らばる時計部品、ダーク
    グラデーション背景、ドラマチックなリムライト、8K
    → 推奨：Nano Banana 2 | Imagen4

12. ラスティックな木のテーブルの上のセラミックコーヒーマグ、精巧な
    ラテアート、窓からの朝日、ぼけたベーカリーの背景
    → 推奨：Seedream v5.0 | Nano Banana 2

13. 大理石の上にスキンケアボトルのフラットレイ、新鮮なユーカリの葉、
    水滴、上からの柔らかい拡散光、クリーンミニマル美学
    → 推奨：Nano Banana 2 | Qwen-Image Max

14. ランニングシューズが水たまりにスプラッシュ、フリーズフレーム、
    都市環境、ドラマチックなローアングル、Nike風商品写真
    → 推奨：Nano Banana 2 | Imagen4

15. ミニマルテックプロダクト：白い面のワイヤレスイヤホンケース、
    ソフトグラデーションシャドウ、Apple風商品写真、完璧な対称
    → 推奨：Z-Image Turbo | Nano Banana 2
```

### 🌸 アニメ・マンガ

```
16. 桜の庭園の精緻なアニメ少女、柔らかいピンクの花びら舞う、伝統的
    着物にモダンスニーカー、暖かい春の日差し、ジブリカラーパレット
    → 推奨：Flux Dev LoRA | Seedream v5.0

17. ホログラフィックディスプレイに囲まれたコックピットのメカパイロット、
    バイザーに宇宙戦闘の反射、ガンダムインスパイア、サンライズ品質
    → 推奨：Flux Dev LoRA | Seedream v5.0

18. 日常シーン：夜の温かいラーメン屋、黄色い光、立ち上る湯気、
    こだわりの老店主、精緻なフードイラスト、新海誠のライティング
    → 推奨：Flux Dev LoRA | Seedream v5.0

19. 魔法少女変身シーンのフリーズフレーム、光のリボンが渦巻く、
    ダイナミックポーズ、きらめく星のエフェクト、鮮やかな色彩
    → 推奨：Flux Dev LoRA

20. アニメ風景：鎖で地上とつながった浮島、雲に落ちる滝、ツタに
    覆われた古代遺跡、ジブリ的ワールドビルディング
    → 推奨：Flux Dev LoRA | Seedream v5.0
```

### 🐉 ファンタジー

```
21. 山頂に鎮座する古代ドラゴン、オーロラを映す鱗、息から形成される
    氷の結晶、精緻な翼膜ディテール、シネマティックエピックファンタジー
    → 推奨：Imagen4 Ultra | Flux Dev

22. 妖精の国の境界のキノコの森、巨大な生物発光キノコ、茎に彫られた
    小さな妖精の家、蛍、魔法の雰囲気
    → 推奨：Flux Dev | Seedream v5.0

23. 中世の錬金術師の研究室、ガラス器具で泡立つ調合物、神秘的な
    記号の古書、機械式アストロラーベ、キャンドルと緑の魔法の光
    → 推奨：Imagen4 | Flux Dev

24. 華麗なダークアーマーの戦士女王が燃える都市の前に立つ、マントが
    たなびく、ルーンが光る伝説の剣、背景のエピックバトルシーン
    → 推奨：Imagen4 Ultra | Flux Dev

25. 水晶と氷でできた魔法の冬の森、頭上のオーロラ、青く光る目の
    白い狐、光を捕らえる雪の粒子、マジカルリアリズム
    → 推奨：Imagen4 Ultra | Nano Banana 2
```

### 🚀 SF

```
26. 熱帯の島から軌道へ伸びる宇宙エレベーター、見える地球の曲率、
    上昇するカーゴポッド、中間部の雲の層、ハードSF、技術的に正確
    → 推奨：Imagen4 Ultra | Flux Dev

27. 廃棄された世代宇宙船の内部、異星の植物に覆われた、壊れた
    クライオポッド、点滅する非常灯、美しい崩壊の雰囲気
    → 推奨：Flux Dev | Imagen4

28. サイバネティック神経インターフェースの装着、首の背面クローズ
    アップ、見える微小ナノボット、手術の精密さ、青いホログラム
    → 推奨：Nano Banana 2 | Imagen4

29. テラフォーミングされた火星コロニー、地平線上の赤い砂嵐、内部に
    緑の庭園が見えるバイオドーム、ソーラーパネル、空に複数の月
    → 推奨：Imagen4 Ultra | Seedream v5.0

30. 量子コンピュータコアルーム、超低温チャンバーで光る浮遊量子ビット、
    ケーブルの霜、青紫の光、クリーンな未来建築
    → 推奨：Nano Banana 2 | Imagen4
```

### 🏞️ 風景・自然

```
31. 完全に静かな高山湖にかかる天の川、星の反射がミラーイメージ、
    松のシルエット、岸辺の生物発光プランクトン、長時間露光、8K
    → 推奨：Imagen4 Ultra | Nano Banana 2

32. プロヴァンスのラベンダー畑の日の出ドローンショット、完璧に
    平行な列が幾何学パターンを作る、谷の朝霧、紫と金のパレット
    → 推奨：Nano Banana 2 | Seedream v5.0

33. 朝霧の古いレッドウッドの森、キャノピーを通る太陽のゴッドレイ、
    森の床を覆うシダ、小さな人影による巨大なスケール感
    → 推奨：Imagen4 Ultra | Nano Banana 2

34. 夜の火山噴火、海に流れ込む溶岩が巨大な蒸気雲を生む、噴煙中の
    雷、長時間露光、ドラマチックな自然写真
    → 推奨：Imagen4 Ultra

35. 日本の秋景色：錦鯉の池にかかる伝統的な赤い橋、完璧に手入れ
    された紅葉のモミジ、さざ波を作る細雨、塔の反射
    → 推奨：Nano Banana 2 | Seedream v5.0
```

---

## 🛠️ ツール＆エコシステム

### ワークフロー＆UIツール

| ツール | 説明 | リンク |
|:------|:-----|:------|
| **ComfyUI** | ノードベースのワークフローエディタ | [GitHub](https://github.com/comfyanonymous/ComfyUI) |
| **Automatic1111** | 人気Stable Diffusion Web UI | [GitHub](https://github.com/AUTOMATIC1111/stable-diffusion-webui) |
| **Fooocus** | Midjourney風の簡略化UI | [GitHub](https://github.com/lllyasviel/Fooocus) |
| **InvokeAI** | プロフェッショナルクリエイティブAIツールキット | [GitHub](https://github.com/invoke-ai/InvokeAI) |

### LoRA＆モデルリポジトリ

| プラットフォーム | 説明 | リンク |
|:---------------|:-----|:------|
| **Civitai** | 最大のコミュニティモデルリポジトリ | [civitai.com](https://civitai.com) |
| **HuggingFace** | オープンモデルハブ | [huggingface.co](https://huggingface.co) |
| **Tensor.Art** | AIアートプラットフォーム | [tensor.art](https://tensor.art) |

### アップスケーラー＆後処理

| ツール | 説明 | リンク |
|:------|:-----|:------|
| **Real-ESRGAN** | 最先端の画像アップスケーリング | [GitHub](https://github.com/xinntao/Real-ESRGAN) |
| **Topaz Gigapixel** | 商用AIアップスケーラー | [topazlabs.com](https://www.topazlabs.com) |
| **CodeFormer** | 顔の修復と強化 | [GitHub](https://github.com/sczhou/CodeFormer) |

---

## 💰 料金詳細

### プロバイダー別料金比較

| プロバイダー | モデル | 画像単価 | 速度 | 品質 |
|:------------|:------|:---------|:-----|:-----|
| **Google** | Nano Banana 2 | $0.072 | ⚡⚡⚡ | ⭐⭐⭐⭐⭐ |
| **Google** | Imagen4 Ultra | ~$0.10+ | ⚡ | ⭐⭐⭐⭐⭐ |
| **Google** | Imagen4 | ~$0.06-0.08 | ⚡⚡ | ⭐⭐⭐⭐ |
| **Google** | Imagen4 Fast | ~$0.04-0.06 | ⚡⚡⚡ | ⭐⭐⭐ |
| **BFL** | Flux Schnell | ~$0.003 | ⚡⚡⚡ | ⭐⭐⭐ |
| **BFL** | Flux Dev | ~$0.03 | ⚡⚡ | ⭐⭐⭐⭐ |
| **ByteDance** | Seedream v5.0 | ~$0.03-0.05 | ⚡⚡ | ⭐⭐⭐⭐ |
| **Alibaba** | Qwen-Image Max | ~$0.02-0.04 | ⚡⚡ | ⭐⭐⭐⭐ |
| **Alibaba** | Z-Image Turbo | ~$0.01-0.02 | ⚡⚡⚡ | ⭐⭐⭐ |

> 💡 **Atlas Cloudの利点：** 全モデル競争力のある価格 + **初回チャージで25%ボーナス（最大$100）**
>
> 👉 [atlascloud.aiで始める](https://www.atlascloud.ai?ref=JPM683)

### Atlas Cloud vs fal.ai — 価格比較

| モデル | fal.ai | Atlas Cloud | 備考 |
|:------|:-------|:-----------|:-----|
| **Nano Banana 2** | $0.0398/枚 | $0.072/枚 | fal.ai の方が1枚あたり安いが、Atlas Cloud は全解像度4Kまで定額 |
| **Flux Kontext Pro** | $0.04/枚 | — | fal.ai で利用可能 |
| **Seedream V4** | $0.03/枚 | $0.032/枚 | ほぼ同等の価格 |
| **Flux Dev** | — | $0.012/枚 | Atlas Cloud は Flux Dev で非常に競争力あり |

> **fal.ai が一部モデルで安くても Atlas Cloud を選ぶ理由は？**
> - **統一API** — 46の画像モデルを1つのAPIキー、1つのエンドポイント、1つの請求で
> - **制限なしモード** — 対応モデルでコンテンツフィルタリングなし
> - **バッチ生成** — 1リクエストで最大15枚生成（Seedream Sequential）
> - **LoRAサポート** — 対応モデル全体でカスタムLoRAを使用
> - **定額制** — 高解像度でも追加料金なし

### コスト最適化のヒント

1. **Flux Schnellで下書き** → プレミアムモデルで仕上げ
2. **バッチモード**を活用（Seedreamシーケンシャル）
3. **低解像度で生成** → Real-ESRGANでアップスケール
4. **プロンプトをキャッシュ** — 効果的なプロンプトを再利用
5. **適切なモデルを選択** — Flux Schnellで十分な場面でImagen4 Ultraは不要

---

## ❓ よくある質問

### 2026年最高のAI画像生成ツールは？

用途によります。**フォトリアリズム**なら **Nano Banana 2** と **Imagen4 Ultra**。**速度とコスト**なら **Flux Schnell**。**バッチ生成**なら **Seedream v5.0**（15枚/バッチ）。**カスタムスタイル**なら **Flux Dev LoRA**。[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683) で全46モデルを1つのAPIで利用可能。

### 最も安いAI画像APIは？

**Flux Schnell** が約$0.003/枚で最安。高品質でコスパなら **Nano Banana 2** が$0.072/枚から。[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683) の **初回チャージ25%ボーナス**（最大$100）でさらにお得に。

### APIでAI画像を生成するには？

[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683) のような統一APIを使用。サインアップしてAPIキーを取得し、プロンプトとモデルを含むHTTPリクエストを送るだけ。上記[クイックスタート](#-クイックスタート--統一api)のcURL、Python、JavaScriptの例を参照。

### Flux vs Nano Banana 2 vs Midjourney — どれが良い？

| 機能 | Flux Dev | Nano Banana 2 | Midjourney |
|:-----|:---------|:--------------|:-----------|
| API対応 | ✅ | ✅ | ❌（Discordのみ） |
| 速度 | ⚡⚡ | ⚡⚡⚡ | ⚡⚡ |
| 品質 | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| LoRA | ✅ | ❌ | ❌ |
| 編集 | ❌（Kontextのみ） | ✅（14参照画像） | 限定的 |
| 検閲なし | ✅（Atlas） | ❌ | ❌ |
| 価格 | ~$0.03 | $0.072 | $10+/月 |

### NSFWコンテンツに最適なAI画像モデルは？

[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683) の **Flux Dev** がコンテンツフィルターなしで無制限生成を提供。他のプロバイダー（Google、ByteDance、Alibaba）はセーフティフィルターを適用。

### バッチで画像生成できますか？

はい！**Seedream v5.0**（v4.5、v4も）はシーケンシャルモードで1リクエストあたり最大**15枚**の画像を生成可能。

### 画像内テキストのレンダリングが最も正確なモデルは？

**Nano Banana 2** がテキストレンダリング精度でリード。読みやすいテキスト、ロゴ、タイポグラフィを含む画像を確実に生成可能。

---

## 🎨 全AI画像モデル、1つのAPI

<div align="center">

**Google、ByteDance、Black Forest Labs、Alibabaの46画像モデル。**

すべてを1つの統一APIで。

| 特徴 | 詳細 |
|:-----|:-----|
| ✅ **46モデル** | 全主要AI画像モデル |
| ✅ **検閲なし** | 対応モデルで完全な創作の自由 |
| ✅ **$0.072から** | 公式APIより安い |
| ✅ **25%ボーナス** | 初回チャージ（最大$100） |
| ✅ **1つのAPIキー** | パラメーター変更でモデル切替 |
| ✅ **バッチ対応** | 1リクエスト最大15枚 |

<br/>

### 👉 [Atlas Cloudで生成を始める](https://www.atlascloud.ai?ref=JPM683)

*初回チャージで25%ボーナス、最大$100*

</div>

---

## 📈 Star履歴

<div align="center">

[![Star History Chart](https://api.star-history.com/svg?repos=atlascloud/awesome-ai-image-generation&type=Date)](https://star-history.com/#atlascloud/awesome-ai-image-generation&Date)

**⭐ リポジトリにStarして最新情報をキャッチ！**

</div>

---

## 🤝 コントリビュート

コントリビューション大歓迎です！Pull Requestをお気軽にどうぞ。

1. リポジトリをフォーク
2. フィーチャーブランチを作成（`git checkout -b feature/add-new-model`）
3. 変更をコミット（`git commit -m '新モデルセクション追加'`）
4. ブランチをプッシュ（`git push origin feature/add-new-model`）
5. Pull Requestを作成

**コントリビュートできる内容：**
- 新モデルやモデル更新
- 結果付きプロンプト例
- ツール推奨
- 翻訳の改善
- バグ修正

---

## 📄 ライセンス

このプロジェクトは **MITライセンス** に基づいています — [LICENSE](LICENSE) ファイルをご覧ください。

---

<div align="center">

**AI画像生成コミュニティが ❤️ を込めて作成**

[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683) · [問題報告](../../issues) · [機能リクエスト](../../issues)

</div>
