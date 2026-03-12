<div align="center">

# 🎨 Awesome AI 图片生成

### 2026 年 AI 图片模型权威指南

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Models](https://img.shields.io/badge/图片模型-46-blue.svg)](https://www.atlascloud.ai?ref=JPM683)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/atlascloud/awesome-ai-image-generation?style=social)](https://github.com/atlascloud/awesome-ai-image-generation)

**精选 AI 图片生成模型、提示词、工具和资源合集**

涵盖 **Google Nano Banana 2 · Imagen4 · ByteDance Seedream · Flux · Wan · Qwen-Image** 等主流模型。

[English](README.md) · [简体中文](README_zh-CN.md) · [日本語](README_ja.md) · [한국어](README_ko.md)

---

**⭐ 如果觉得有用，请 Star 本仓库 — 帮助更多人发现它！**

</div>

---

## 🚀 赞助 — 46 个图片模型，一个 API

<div align="center">

**[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)** — 所有主流 AI 图片模型的统一 API。

一个 API Key，46 个图片模型。Google、ByteDance、Black Forest Labs、阿里巴巴 — 全部集成。

🎁 **首充赠送 25%（最高 $100）**

[![试用 Atlas Cloud](https://img.shields.io/badge/试用_Atlas_Cloud-免费额度-blue?style=for-the-badge)](https://www.atlascloud.ai?ref=JPM683)

> 🔒 **企业级安全保障** — Atlas Cloud 已通过 **SOC I & II 认证** | **HIPAA 合规** | 美国公司，99.9% 正常运行时间 SLA。

> 💳 **支付便捷** — 支持微信支付、支付宝直接付款，无需国际信用卡。

</div>

---

## 📑 目录

- [2026 AI 图片模型全景](#-2026-ai-图片模型全景)
- [Google 模型](#-google-模型)
  - [Nano Banana 2](#nano-banana-2)
  - [Imagen4 系列](#imagen4-系列)
- [字节跳动 Seedream](#-字节跳动-seedream)
  - [Seedream v5.0 Lite](#seedream-v50-lite)
  - [Seedream v4.5](#seedream-v45)
  - [Seedream v4](#seedream-v4)
- [Black Forest Labs — Flux](#-black-forest-labs--flux)
  - [Flux Dev 与 Schnell](#flux-dev-与-schnell)
  - [Flux LoRA](#flux-lora)
  - [Flux Kontext](#flux-kontext)
- [阿里巴巴模型](#-阿里巴巴模型)
  - [Wan 2.6 / 2.5](#wan-26--25)
  - [Qwen-Image 通义万相](#qwen-image-通义万相)
  - [Z-Image Turbo](#z-image-turbo)
- [使用场景推荐](#-使用场景推荐)
- [快速开始 — 统一 API](#-快速开始--统一-api)
- [提示词工程大师指南](#-提示词工程大师指南)
- [提示词合集（50+）](#-提示词合集50-条)
- [工具与生态](#-工具与生态)
- [定价详解](#-定价详解)
- [常见问题](#-常见问题)
- [Star 历史](#-star-历史)
- [贡献指南](#-贡献指南)
- [许可证](#-许可证)

---

## 📊 2026 AI 图片模型全景

> 2026 年所有主流 AI 图片模型的综合对比。

| 模型 | 提供商 | 类型 | 最大分辨率 | 速度 | 编辑 | LoRA | 批量 | API 价格 |
|:-----|:-------|:-----|:----------|:-----|:-----|:-----|:-----|:---------|
| **Nano Banana 2** | Google | 文生图 / 编辑 | 4K | ⚡⚡⚡ | ✅ | ❌ | ❌ | $0.072/张起 |
| **Nano Banana 2 Dev** | Google | 文生图 / 编辑 | 4K | ⚡⚡⚡ | ✅ | ❌ | ❌ | $0.072/张起 |
| **Nano Banana Pro** | Google | 文生图 / 编辑 | 4K | ⚡⚡ | ✅ | ❌ | ❌ | 浮动 |
| **Nano Banana** | Google | 文生图 / 编辑 | 2K | ⚡⚡ | ✅ | ❌ | ❌ | 浮动 |
| **Imagen4 Ultra** | Google | 文生图 | 4K | ⚡ | ❌ | ❌ | ❌ | 较高 |
| **Imagen4** | Google | 文生图 | 4K | ⚡⚡ | ❌ | ❌ | ❌ | 浮动 |
| **Imagen4 Fast** | Google | 文生图 | 2K | ⚡⚡⚡ | ❌ | ❌ | ❌ | 浮动 |
| **Imagen3** | Google | 文生图 | 2K | ⚡⚡ | ❌ | ❌ | ❌ | 浮动 |
| **Imagen3 Fast** | Google | 文生图 | 2K | ⚡⚡⚡ | ❌ | ❌ | ❌ | 浮动 |
| **Seedream v5.0 Lite** | 字节跳动 | 文生图 / 编辑 | 2K | ⚡⚡ | ✅ | ❌ | ✅ 15张 | 浮动 |
| **Seedream v4.5** | 字节跳动 | 文生图 / 编辑 | 2K | ⚡⚡ | ✅ | ❌ | ✅ 15张 | 浮动 |
| **Seedream v4** | 字节跳动 | 文生图 / 编辑 | 2K | ⚡⚡ | ✅ | ❌ | ✅ 15张 | 浮动 |
| **Flux Dev** | BFL | 文生图 | 2K | ⚡⚡ | ❌ | ✅ | ❌ | 浮动 |
| **Flux Schnell** | BFL | 文生图 | 1K | ⚡⚡⚡ | ❌ | ❌ | ❌ | 最低 |
| **Flux Dev LoRA** | BFL | 文生图 | 2K | ⚡⚡ | ❌ | ✅ | ❌ | 浮动 |
| **Flux Kontext Dev** | BFL | 编辑 | 2K | ⚡⚡ | ✅ | ❌ | ❌ | 浮动 |
| **Flux Kontext Dev LoRA** | BFL | 编辑 | 2K | ⚡⚡ | ✅ | ✅ | ❌ | 浮动 |
| **Wan 2.6 文生图** | 阿里巴巴 | 文生图 | 2K | ⚡⚡ | ❌ | ❌ | ❌ | 浮动 |
| **Wan 2.6 编辑** | 阿里巴巴 | 编辑 | 2K | ⚡⚡ | ✅ | ❌ | ❌ | 浮动 |
| **Wan 2.5 文生图** | 阿里巴巴 | 文生图 | 2K | ⚡⚡ | ❌ | ❌ | ❌ | 浮动 |
| **Wan 2.5 编辑** | 阿里巴巴 | 编辑 | 2K | ⚡⚡ | ✅ | ❌ | ❌ | 浮动 |
| **Qwen-Image Max** | 阿里巴巴 | 文生图 | 2K | ⚡⚡ | ❌ | ❌ | ❌ | 浮动 |
| **Qwen-Image Plus** | 阿里巴巴 | 文生图 | 2K | ⚡⚡ | ❌ | ❌ | ❌ | 浮动 |
| **Qwen-Image 编辑** | 阿里巴巴 | 编辑 | 2K | ⚡⚡ | ✅ | ❌ | ❌ | 浮动 |
| **Qwen-Image 编辑 Plus** | 阿里巴巴 | 编辑 | 2K | ⚡⚡ | ✅ | ❌ | ❌ | 浮动 |
| **Z-Image Turbo** | 阿里巴巴 | 文生图 | 2K | ⚡⚡⚡ | ❌ | ❌ | ❌ | 浮动 |

> 💡 **全部 46 个模型通过一个 API 即可使用** — [Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)

---

## 🔷 Google 模型

### Nano Banana 2

> **Google 最新最快的图片生成模型（2026）。** Nano Banana 2 以极速推理生成照片级真实图片，支持最多 14 张参考图片的原生编辑，以及卓越的文字渲染能力。

**核心特性：**
- 🏎️ **极速生成** — 大多数提示词亚秒级推理
- 🎯 **14 张参考图** — 业界领先的图片编辑和风格迁移
- ✍️ **文字渲染** — 准确的文字排版和定位
- 🖼️ **4K 输出** — 超高分辨率
- 💰 **$0.072/张起** — 性价比极高的高端模型

**变体：**
| 变体 | 最佳用途 | 编辑 | 速度 |
|:-----|:---------|:-----|:-----|
| Nano Banana 2 文生图 | 文字生成图片 | ❌ | ⚡⚡⚡ |
| Nano Banana 2 编辑 | 图片编辑 | ✅（14 张参考） | ⚡⚡⚡ |
| Nano Banana 2 开发者 文生图 | 开发/测试 | ❌ | ⚡⚡⚡ |
| Nano Banana 2 开发者 编辑 | 开发/测试 | ✅ | ⚡⚡⚡ |

**Nano Banana 2 示例提示词：**

```
1. 超写实人像：一位年轻女性的特写肖像，脸上有雀斑，金色夕阳光线
   穿透她的赤褐色头发，浅景深，哈苏 X2D 拍摄，100mm f/1.4

2. 午夜生物荧光海滩俯瞰图，海浪发出电蓝色光芒，深色火山砂，
   潮汐池中映着星星，国家地理品质

3. 蒸汽朋克咖啡店内景，墙上有黄铜管道和齿轮，铜制浓缩咖啡机
   冒着蒸汽，温暖的琥珀色灯光，复古皮革座椅，超精细 4K 渲染

4. 产品摄影：大理石台面上的奢华香水瓶，水滴折射出棱镜光芒，
   深色氛围感背景，商业广告品质，8K 分辨率

5. 字体设计：「未来」二字以铬金属液态字母呈现，漂浮在霓虹都市
   上空，湿润路面的倒影，赛博朋克美学，电影级灯光
```

### Imagen4 系列

> **Google 旗舰图片生成套件。** Imagen4 提供三个层级，满足不同的质量/速度需求。

| 模型 | 质量 | 速度 | 最佳用途 |
|:-----|:-----|:-----|:---------|
| **Imagen4 Ultra** | ⭐⭐⭐⭐⭐ | ⚡ | 最高质量、艺术创作、印刷 |
| **Imagen4** | ⭐⭐⭐⭐ | ⚡⚡ | 质量与速度平衡 |
| **Imagen4 Fast** | ⭐⭐⭐ | ⚡⚡⚡ | 快速原型、预览 |

**Imagen4 Ultra** 是单图质量的黄金标准，擅长：
- 超精细细节和纹理渲染
- 复杂多主体构图
- 照片级人体解剖
- 艺术风格复现

**Imagen4 Ultra 示例提示词：**

```
1. 文艺复兴风格油画描绘现代都市黄昏，戏剧性明暗对比，可见笔触，
   金箔点缀，博物馆级别细节，荷兰大师风格

2. 蝴蝶翅膀的极端微距照片，彩虹色鳞片反射，露珠充当微型透镜，
   焦点堆叠，尼康 Z9 配 105mm 微距镜头

3. 科幻电影剧照：一名宇航员独自站在外星世界的水晶峡谷边缘，
   双日落，体积雾，IMAX 品质，维伦纽瓦导演风格

4. 超精细建筑可视化：未来主义日式寺庙，传统木榫工艺结合参数化
   设计，樱花，晨雾，黄金比例构图

5. 超写实静物：古董科学仪器——黄铜望远镜、星盘、罗盘、古地图——
   摆放在红木书桌上，烛光，维米尔式光线，8K 超精细
```

---

## 🟢 字节跳动 Seedream

### Seedream v5.0 Lite

> **字节跳动最新图片模型（2026）。** Seedream v5.0 Lite 提升了提示词遵循度、人体解剖质量，并支持单次请求批量生成最多 15 张图片。

**核心特性：**
- 📦 **批量 15 张** — 一次 API 调用生成最多 15 个变体
- ✏️ **编辑 + 序列** — 高级编辑与序列处理
- 🎨 **中英双语** — 原生双语提示词支持
- ⚡ **快速推理** — 为高吞吐量生产优化

**Seedream v5.0 vs v4.5 对比：**

| 特性 | v5.0 Lite | v4.5 | v4 |
|:-----|:----------|:-----|:---|
| 提示词遵循 | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ |
| 人体解剖 | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ |
| 文字渲染 | ⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ |
| 速度 | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| 批量（序列） | ✅ 15张 | ✅ 15张 | ✅ 15张 |
| 编辑 | ✅ | ✅ | ✅ |

**Seedream v5.0 示例提示词：**

```
1. 中国水墨画以鲜艳数字色彩重新演绎，云雾缭绕的山脉，飞流直下
   的瀑布，桥上独坐的文人，传统构图配现代色彩

2. 超写实美食摄影：一碗日式豚骨拉面，热气升腾，完美的溏心蛋，
   叉烧肉、海苔、葱花，45 度角拍摄，餐厅灯光

3. 2050 年未来上海天际线，飞行器穿梭在有机造型摩天楼之间，全息
   广告，落日映出紫橙色云彩，电影级广角镜头

4. 时尚大片：模特穿着前卫几何服装站在无限镜像房间中，草间弥生
   风格，戏剧性工作室灯光，Vogue 杂志品质

5. 魔法图书馆，无限漂浮的书架螺旋延伸至天空，金色尘埃微粒，
   刻有发光符文的古书，温暖烛光，奇幻概念艺术
```

**序列模式（批量生成）：**

Seedream 的序列模式适用于：
- 产品变体生成（颜色、角度）
- 故事板序列创建
- A/B 测试不同构图
- 批量社交媒体内容创作

---

## ⬛ Black Forest Labs — Flux

### Flux Dev 与 Schnell

> **开源生力军。** Flux 已成为 AI 图片生成社区的骨干力量，拥有无与伦比的 LoRA 生态系统。

| 模型 | 速度 | 质量 | 最佳用途 |
|:-----|:-----|:-----|:---------|
| **Flux Dev** | ⚡⚡ | ⭐⭐⭐⭐ | 生产环境、质量优先 |
| **Flux Schnell** | ⚡⚡⚡ | ⭐⭐⭐ | 最快、最便宜、原型设计 |

**Flux Dev** 优势：
- 🎭 **社区 LoRA 支持** — 数千种社区训练风格
- 🔓 **Atlas Cloud 上无审查** — 完全创作自由
- 🎨 **出色的构图** — 强大的空间关系理解
- 📝 **良好的文字渲染** — 优于大多数开源模型

### Flux LoRA

> **自定义风格生成** — 使用社区训练的 LoRA 模型。

**Flux Dev LoRA** 开启了庞大的自定义风格生态：
- 动漫/漫画风格
- 特定艺术家美学
- 品牌一致性图像
- 产品摄影风格
- 建筑可视化风格

### Flux Kontext

> **上下文图片编辑** — 通过文字指令编辑现有图片。

**Flux 示例提示词：**

```
1. [Flux Dev] 双重曝光摄影，狼脸与北方松林融合，月光，神秘氛围，
   艺术摄影，黑白微蓝色调

2. [Flux Dev] 等距 3D 渲染的温馨微型公寓，小台灯温暖的光线，
   窗台上的绿植，沙发上睡着的猫，体素风格，移轴效果，柔和配色

3. [Flux Schnell] 快速概念草图：机器人咖啡师制作拉花，蒸汽朋克
   咖啡馆，暖色调，插画风格

4. [Flux Kontext] 编辑图片：将背景替换为热带海滩日落，保持主体
   不变，保持自然光线一致性

5. [Flux Dev LoRA] 吉卜力风格：覆满野花的魔法浮空岛，古老石头
   废墟，一个打着红伞的女孩站在边缘，云朵在下方，温暖的午后光线
```

---

## 🟡 阿里巴巴模型

### Wan 2.6 / 2.5

> **阿里巴巴的多模态重器。** Wan 不仅以视频生成闻名，在图片生成和编辑方面同样出色。

| 模型 | 类型 | 优势 |
|:-----|:-----|:-----|
| **Wan 2.6 文生图** | 文生图 | 最新质量，最佳提示词遵循 |
| **Wan 2.6 编辑** | 图片编辑 | 高级编辑能力 |
| **Wan 2.5 文生图** | 文生图 | 成熟稳定 |
| **Wan 2.5 编辑** | 图片编辑 | 可靠的编辑功能 |

### Qwen-Image 通义万相

> **阿里巴巴 Qwen 驱动的图片生成家族。** 强大的中英双语支持，多个质量层级。

| 模型 | 类型 | 最佳用途 |
|:-----|:-----|:---------|
| **Qwen-Image Max** | 文生图 | 最高质量 |
| **Qwen-Image Plus** | 文生图 | 均衡 |
| **Qwen-Image 编辑** | 编辑 | 基础编辑 |
| **Qwen-Image 编辑 Plus** | 编辑 | 高级编辑 |

### Z-Image Turbo

> **速度优先模型** — 低成本快速生成。

**阿里巴巴模型示例提示词：**

```
1. [Wan 2.6] 宁静的秋日禅意花园，耙理沙纹，苔藓覆盖的石头，
   石钵中漂浮着一片红枫叶，竹林过滤的柔和晨光，超精细

2. [Qwen-Image Max] 热闹的春节庆祝场景，传统舞龙，红灯笼点缀
   古街，烟花绽放在宝塔上空，喜庆的人群，电影级广角

3. [Wan 2.6 编辑] 将白天的城市风景转换为赛博朋克夜景，添加霓虹
   招牌、全息广告牌和雨后反光的街道

4. [Qwen-Image Plus] 水彩画风格的欧洲乡村集市，新鲜农产品摊位，
   鹅卵石街道，晨雾，温暖的金色光线，迷人的异想风格

5. [Z-Image Turbo] 产品图：极简无线耳机放在干净白色表面上，柔和
   工作室灯光，轻微反光，苹果式商业摄影风格
```

---

## 🎯 使用场景推荐

> 为你的具体需求选择最佳模型。

| 使用场景 | 推荐模型 | 原因 | 估算价格 |
|:---------|:---------|:-----|:---------|
| ⚡ 速度 / 原型 | **Flux Schnell** | 最快生成，亚秒级 | 最便宜 |
| 📷 照片写实 | **Nano Banana 2** | 最逼真的输出，4K | $0.072/张起 |
| 🏆 最高质量 | **Imagen4 Ultra** | 最佳细节，博物馆品质 | 较高 |
| 📦 批量生成 | **Seedream v5.0** | 每批 15 张图片 | 浮动 |
| 🎨 自定义风格 | **Flux Dev LoRA** | 数千种社区 LoRA | 浮动 |
| ✏️ 图片编辑 | **Nano Banana 2 编辑** | 支持 14 张参考图 | $0.072/张起 |
| 💰 预算优先 | **Flux Schnell** | 单张成本最低 | 最低 |
| 🔓 无审查 / NSFW | **Flux Dev**（Atlas） | Atlas 上无内容过滤 | 浮动 |
| 🇨🇳 中文提示词 | **Seedream v5.0** | 原生中英双语支持 | 浮动 |
| 📝 图中文字 | **Nano Banana 2** | 最佳文字渲染精度 | $0.072/张起 |
| 🏢 企业级 | **Imagen4** | Google 品质，稳定可靠 | 浮动 |
| 🖼️ 概念艺术 | **Flux Dev** | 强大的艺术构图能力 | 浮动 |

---

## ⚡ 快速开始 — 统一 API

> **一个 API，全部 46 个模型。** 更换模型只需修改一个参数。

### cURL

```bash
# 文本生成图片 — Nano Banana 2
curl -X POST "https://api.atlascloud.ai/v1/images/generations" \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "nano-banana-2",
    "prompt": "超写实人像，黄金时刻光线，浅景深",
    "size": "1024x1024",
    "n": 1
  }'
```

### Python

```python
# 使用 Atlas Cloud 统一 API 生成图片
import requests

API_KEY = "YOUR_API_KEY"
BASE_URL = "https://api.atlascloud.ai/v1"

def generate_image(prompt, model="nano-banana-2", size="1024x1024"):
    """
    通过统一 API 生成图片。
    支持所有 46 个图片模型，只需更改 model 参数。
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

# 使用不同模型生成图片 — 只需更改 model 参数
result_nb2 = generate_image(
    "壮丽的山脉日落",
    model="nano-banana-2"        # Google 最新模型
)

result_flux = generate_image(
    "壮丽的山脉日落",
    model="flux-dev"             # Flux 开源模型
)

result_seedream = generate_image(
    "壮丽的山脉日落",
    model="seedream-v5-lite"     # 字节跳动最新模型
)

# 打印结果
print(result_nb2)
```

### JavaScript / Node.js

```javascript
// 使用 Atlas Cloud 统一 API 生成图片
const API_KEY = "YOUR_API_KEY";
const BASE_URL = "https://api.atlascloud.ai/v1";

/**
 * 生成图片 — 支持所有 46 个模型
 * @param {string} prompt - 图片描述
 * @param {string} model - 模型名称
 * @param {string} size - 输出尺寸
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

// 使用示例
(async () => {
  const result = await generateImage(
    "赛博朋克夜景城市，霓虹灯，细雨",
    "nano-banana-2"
  );
  console.log("生成结果:", result);
})();
```

> 📖 完整 API 文档：[Atlas Cloud Docs](https://www.atlascloud.ai?ref=JPM683)

---

## 🧠 提示词工程大师指南

### 通用原则

每个优秀的提示词都遵循一个结构，所有模型通用：

```
[主体] + [风格/媒介] + [构图] + [光线] + [质量修饰词]
```

**1. 主体 — 要具体**
| 弱 ❌ | 强 ✅ |
|:------|:------|
| 一个女人 | 一位 25 岁的短发东亚女性 |
| 一座城市 | 凌晨 2 点雨后的东京小巷 |
| 一朵花 | 一朵带着晨露的白色牡丹 |

**2. 风格与媒介关键词**

| 类别 | 关键词 |
|:-----|:-------|
| 摄影 | 单反、胶片摄影、宝丽来、航拍、微距、移轴 |
| 数字艺术 | 概念艺术、数字绘画、接景绘画、3D 渲染、CGI |
| 传统艺术 | 油画、水彩、水墨、炭笔、铅笔素描 |
| 插画 | 矢量图、扁平设计、等距、线描、漫画书 |
| 特定风格 | 吉卜力、新艺术运动、包豪斯、蒸汽波、赛博朋克 |

**3. 构图技巧**

| 技巧 | 描述 | 示例 |
|:-----|:-----|:-----|
| 三分法 | 主体偏离中心 | "主体位于画面右三分之一处" |
| 引导线 | 线条引导视线 | "铁轨延伸至地平线" |
| 对称 | 平衡构图 | "完美对称的寺庙入口" |
| 画中画 | 自然框架 | "透过石拱门观看" |
| 鸟瞰 | 俯视视角 | "花园的高空俯瞰视角" |
| 仰视 | 低角度 | "从地面仰视拍摄" |

**4. 光线词汇**

| 光线类型 | 效果 | 最佳用途 |
|:---------|:-----|:---------|
| 黄金时刻 | 温暖、柔和、定向 | 人像、风景 |
| 蓝色时刻 | 冷调、空灵 | 城市风景、氛围 |
| 伦勃朗光 | 面颊上戏剧性三角光 | 人像 |
| 轮廓光 | 发光边缘 | 剪影、戏剧性 |
| 体积光 | 可见光线 | 奇幻、氛围感 |
| 明暗法 | 强烈明暗对比 | 艺术、戏剧性 |
| 霓虹灯光 | 彩色人工辉光 | 赛博朋克、夜生活 |

**5. 质量与分辨率修饰词**

```
超精细、8K 分辨率、高度细节、杰作品质、
专业摄影、获奖作品、锐利对焦、精细细节、
体积渲染、光线追踪、次表面散射
```

### 模型专属技巧

**Nano Banana 2：**
- 擅长相机/镜头参数（如"Sony A7R V 拍摄，85mm f/1.2"）
- 文字渲染：将目标文字放在引号中
- 参考图片能大幅提升一致性

**Seedream v5.0：**
- 原生支持中文提示词 — 可尝试中英双语
- 序列模式：以编号列表描述变体
- 擅长亚洲美学和文化元素

**Flux Dev：**
- 更长、更详细的提示词效果更好
- LoRA 触发词必须出现在提示词中
- 自然语言比关键词列表效果更好

---

## 🎁 提示词合集（50+ 条）

### 📷 照片写实

```
1. 一位日本老渔夫的超写实特写肖像，深深的皱纹诉说着数十年的
   海上故事，花白的胡茬，风化的渔帽，黄金时刻光线洒在脸上，
   大海和渔船的虚化背景，Canon EOS R5，135mm f/2，8K
   → 推荐：Nano Banana 2 | Imagen4 Ultra

2. 挪威峡湾秋季航拍，翡翠色湖水映照橙红色山脉，岸边一座小红屋，
   晨雾悬浮在水面上方，DJI Mavic 3 品质，国家地理封面照
   → 推荐：Imagen4 Ultra | Nano Banana 2

3. 首尔雨夜街头摄影，霓虹招牌映在湿润路面上，一个打透明伞的
   孤独身影，浅景深，Leica M11，柯达 Portra 800 胶片模拟
   → 推荐：Nano Banana 2 | Flux Dev

4. 跳蛛停在带露珠的玫瑰花瓣上的微距摄影，彩虹色螯肢，八只眼睛
   映照着摄影师，极端细节的毛状刚毛，Laowa 25mm 微距，焦点堆叠
   → 推荐：Imagen4 Ultra

5. 北欧极简主义住宅的超写实内景，落地窗外是雪覆盖的森林，温暖
   木质色调，Eames 躺椅，壁炉，hygge 氛围，Dwell 杂志风格
   → 推荐：Nano Banana 2 | Seedream v5.0
```

### 🎨 数字艺术与概念艺术

```
6. 一棵巨大古树穿透废弃的大教堂生长，树根缠绕石柱，彩色玻璃窗
   透过尘埃投射彩色光束，到处是苔藓和蕨类，概念艺术，ArtStation 趋势
   → 推荐：Flux Dev | Imagen4

7. 赛博朋克武士站在东京屋顶，武士刀反射霓虹城市灯光，机械臂
   露出可见伺服电机，全息 HUD 面罩，雨落，动漫风概念艺术
   → 推荐：Flux Dev | Seedream v5.0

8. 水下文明，生物发光建筑，水母形状的建筑物，鱼群如交通，
   珊瑚覆盖的桥梁，深海蓝渐变，游戏概念艺术
   → 推荐：Imagen4 Ultra | Flux Dev

9. 温馨的女巫小屋内景，架子上的药水冒泡，黑猫趴在魔法书堆上，
   天花板上晾着草药，温暖壁炉光，漂浮蜡烛，吉卜力风格遇上暗黑学院
   → 推荐：Flux Dev LoRA | Seedream v5.0

10. 蒸汽朋克飞艇停靠站在云端之上，黄铜和铜质建筑，巨型螺旋桨，
    维多利亚风格乘客走在舷梯上，体积云光，接景绘画风格
    → 推荐：Imagen4 Ultra | Flux Dev
```

### 📦 产品摄影

```
11. 奢华机械腕表悬浮在半空中，周围散落手表零件，暗色渐变背景，
    戏剧性轮廓光，可见齿轮机构，商业广告品质，8K
    → 推荐：Nano Banana 2 | Imagen4

12. 陶瓷咖啡杯放在质朴木桌上，拿铁上精致的拉花，晨光透过窗户
    洒入，模糊的烘焙坊背景，生活方式产品照
    → 推荐：Seedream v5.0 | Nano Banana 2

13. 俯拍护肤品瓶子排列在大理石上，新鲜植物装饰，尤加利叶，
    水滴，从上方柔和漫射灯光，极简美学
    → 推荐：Nano Banana 2 | Qwen-Image Max

14. 一双跑鞋溅入水坑，定格水花动态，城市环境，戏剧性低角度，
    耐克式商业摄影，逆光
    → 推荐：Nano Banana 2 | Imagen4

15. 极简科技产品：无线耳机盒放在干净白色表面上，柔和渐变阴影，
    苹果风格产品摄影，完美对称，4K 商业品质
    → 推荐：Z-Image Turbo | Nano Banana 2
```

### 🌌 抽象与实验

```
16. 抽象流体艺术：碰撞的星系渲染为水中墨滴，宇宙紫金色彩，
    漩涡中的数学分形，不可能物理的微距摄影
    → 推荐：Imagen4 Ultra | Flux Dev

17. 超正方体在三维空间中展开，几何不可能建筑，埃舍尔遇上现代
    数学，纯白背景，精确线条配微妙色彩渐变
    → 推荐：Imagen4 | Flux Dev

18. 共感觉可视化：贝多芬月光奏鸣曲的视觉景观，银色月光束为垂直
    线条，深蓝波浪为低音，金色火花为高音，抽象表现主义
    → 推荐：Imagen4 Ultra

19. 想象中矿物的微观视图：不可能色彩的结晶结构，分形生长图案，
    生物发光脉络，科学插画遇上迷幻艺术
    → 推荐：Imagen4 Ultra | Flux Dev

20. 数据可视化艺术：城市 Wi-Fi 信号渲染为建筑间流动的极光般波浪，
    暗色背景，长曝光风格，科学与艺术结合
    → 推荐：Flux Dev | Seedream v5.0
```

### 🌸 动漫与漫画

```
21. 精细动漫女孩在樱花花园中，柔粉色花瓣飘落，传统和服搭配现代
    运动鞋，温暖春日阳光，吉卜力色调，微风拂过秀发
    → 推荐：Flux Dev LoRA | Seedream v5.0

22. 机甲驾驶员在充满全息显示屏的驾驶舱内，坚定的表情，护目镜
    反射太空战斗，高达风格设计，日升社品质
    → 推荐：Flux Dev LoRA | Seedream v5.0

23. 日常生活场景：夜晚温馨的拉面店，温黄灯光，蒸汽升腾，专注
    制面的老师傅，精细食物插画，新海诚光影风格
    → 推荐：Flux Dev LoRA | Seedream v5.0

24. 魔法少女变身瞬间定格，光之缎带旋转，动感姿态，星光闪烁效果，
    美少女战士遇上现代动漫美学，鲜艳色彩
    → 推荐：Flux Dev LoRA

25. 动漫风景：用锁链连接地面的浮空岛，瀑布倾泻入云层，藤蔓缠绕
    的古代遗迹，吉卜力式世界构建
    → 推荐：Flux Dev LoRA | Seedream v5.0
```

### 🐉 奇幻

```
26. 古龙盘踞在山巅，鳞片映射北极光，呼吸中形成冰晶，精细的翼膜
    细节，电影级史诗奇幻，8K 超精细
    → 推荐：Imagen4 Ultra | Flux Dev

27. 仙境边缘的蘑菇森林，巨型生物发光蘑菇，蘑菇茎上雕刻的小精灵
    房屋，萤火虫，魔法氛围，充满奇趣
    → 推荐：Flux Dev | Seedream v5.0

28. 中世纪炼金术士的实验室，玻璃器皿中冒泡的混合物，刻有神秘
    符号的古书，机械星盘，烛光与魔法绿光
    → 推荐：Imagen4 | Flux Dev

29. 身着华丽暗铠甲的女战士女王站在燃烧的城市前，披风飘扬，传奇
    之剑刻着发光符文，背景是史诗战斗场景，油画风格
    → 推荐：Imagen4 Ultra | Flux Dev

30. 水晶和冰构成的魔法冬日森林，头顶北极光，蓝色发光眼睛的白狐，
    雪花颗粒捕捉光线，魔幻写实主义
    → 推荐：Imagen4 Ultra | Nano Banana 2
```

### 🚀 科幻

```
31. 从热带岛屿延伸至轨道的太空电梯，可见地球弧度，上升的货物舱，
    中段的云层，硬科幻，技术精确，电影级渲染
    → 推荐：Imagen4 Ultra | Flux Dev

32. 废弃世代飞船内部，被外星植被覆盖，损坏的冷冻舱，闪烁的应急
    灯光，美丽衰败的氛围，3A 游戏概念艺术
    → 推荐：Flux Dev | Imagen4

33. 安装仿生神经接口的特写，颈后部位，可见微型纳米机器人，手术
    精度，蓝色全息引导，医学科幻，照片级写实
    → 推荐：Nano Banana 2 | Imagen4

34. 改造后的火星殖民地，地平线上的红色沙尘暴，内部可见绿色花园
    的生物穹顶栖息地，太阳能板，天空中多颗卫星，黄金时刻
    → 推荐：Imagen4 Ultra | Seedream v5.0

35. 量子计算机核心机房，超低温腔体中悬浮发光的量子比特，电缆上
    结霜，蓝紫色光线，洁净未来建筑，技术崇高感
    → 推荐：Nano Banana 2 | Imagen4
```

### 👤 人像

```
36. 戏剧性工作室肖像，左侧单点主光，深阴影，一位音乐家手持复古
    萨克斯管，烟雾缭绕，黑色背景，Irving Penn 风格
    → 推荐：Nano Banana 2 | Imagen4

37. 女性海洋生物学家的环境人像，水下被银色鱼群环绕，潜水装备，
    自然海洋光线，国家地理人像风格
    → 推荐：Imagen4 Ultra | Nano Banana 2

38. 高端时尚编辑人像，模特画着金银几何面妆，背梳发型，纯白背景，
    Alexander McQueen 美学，Vogue 封面品质
    → 推荐：Seedream v5.0 | Nano Banana 2

39. John Singer Sargent 风格油画肖像，黑暗音乐厅中的年轻小提琴手，
    戏剧性聚光灯，可见笔触，丰富暗色调配发光肤色
    → 推荐：Imagen4 Ultra

40. 纹身艺术家工作中的街头肖像，沾满墨水的双手特写，选择性对焦，
    工业工作空间背景，纪实摄影风格
    → 推荐：Nano Banana 2 | Flux Dev
```

### 🏞️ 风景与自然

```
41. 银河拱跨完美平静的高山湖泊，星星倒影创造镜像，剪影松树，
    岸边生物发光浮游生物，长曝光天文摄影，8K
    → 推荐：Imagen4 Ultra | Nano Banana 2

42. 普罗旺斯薰衣草田日出无人机拍摄，完美平行的行列创造几何图案，
    山谷中的晨雾，温暖的紫金配色，DJI 品质
    → 推荐：Nano Banana 2 | Seedream v5.0

43. 晨雾中的古老红杉森林，阳光穿透树冠创造丁达尔效应，蕨类植物
    铺满森林地面，巨大尺度感中渺小的人影
    → 推荐：Imagen4 Ultra | Nano Banana 2

44. 夜晚的火山喷发，熔岩流入大海产生大量蒸汽云，火山烟柱中的
    闪电，长曝光，戏剧性自然摄影，国家地理品质
    → 推荐：Imagen4 Ultra

45. 日本秋景：锦鲤池塘上的传统红桥，精心修剪的枫树满是秋色，
    细雨在水面泛起涟漪，宝塔倒影，富士 Velvia 50 色彩渲染
    → 推荐：Nano Banana 2 | Seedream v5.0
```

### 🔥 进阶提示词

```
46. [多主体] 维多利亚图书馆中机器人与巫师的国际象棋对弈，棋盘上
    每颗棋子都是微型活物，戏剧性侧光，广角捕捉全景，8K
    → 推荐：Imagen4 Ultra

47. [跨风格] 分屏画面：左半部分是超写实森林，右半部分同一场景
    变为梵高油画风格，中间无缝过渡
    → 推荐：Nano Banana 2 | Imagen4

48. [建筑] 海浪灵感参数化建筑博物馆，流动的混凝土形态，落地玻璃，
    倒影池，黄金时刻，扎哈·哈迪德风格，ArchDaily 品质渲染
    → 推荐：Imagen4 Ultra | Nano Banana 2

49. [文化] 热闹的亡灵节庆祝，微笑女性脸上华丽的骷髅面妆，万寿菊
    花冠，烛光照亮的祭坛背景，温暖喜庆的氛围
    → 推荐：Seedream v5.0 | Nano Banana 2

50. [超现实] 巨大鲸鱼在欧洲小村庄上空的云层中游泳，村民仰望惊叹，
    魔幻现实主义，宫崎骏遇上马格利特，梦幻午后光线
    → 推荐：Flux Dev | Imagen4
```

---

## 🛠️ 工具与生态

### 工作流与 UI 工具

| 工具 | 描述 | 链接 |
|:-----|:-----|:-----|
| **ComfyUI** | 节点式工作流编辑器 | [GitHub](https://github.com/comfyanonymous/ComfyUI) |
| **Automatic1111** | 热门 Stable Diffusion Web UI | [GitHub](https://github.com/AUTOMATIC1111/stable-diffusion-webui) |
| **Fooocus** | 简化版 UI，灵感来自 Midjourney | [GitHub](https://github.com/lllyasviel/Fooocus) |
| **InvokeAI** | 专业创意 AI 工具包 | [GitHub](https://github.com/invoke-ai/InvokeAI) |

### LoRA 与模型仓库

| 平台 | 描述 | 链接 |
|:-----|:-----|:-----|
| **Civitai** | 最大的社区模型仓库 | [civitai.com](https://civitai.com) |
| **HuggingFace** | 开放模型中心 | [huggingface.co](https://huggingface.co) |
| **Tensor.Art** | AI 艺术平台 | [tensor.art](https://tensor.art) |

### 超分辨率与后处理

| 工具 | 描述 | 链接 |
|:-----|:-----|:-----|
| **Real-ESRGAN** | 最先进的图片放大 | [GitHub](https://github.com/xinntao/Real-ESRGAN) |
| **Topaz Gigapixel** | 商业 AI 放大器 | [topazlabs.com](https://www.topazlabs.com) |
| **CodeFormer** | 人脸修复与增强 | [GitHub](https://github.com/sczhou/CodeFormer) |
| **GFPGAN** | 人脸修复 | [GitHub](https://github.com/TencentARC/GFPGAN) |

### 图片编辑与增强

| 工具 | 描述 | 链接 |
|:-----|:-----|:-----|
| **SAM 2** | Meta 通用分割模型 | [GitHub](https://github.com/facebookresearch/sam2) |
| **Remove.bg** | 背景移除 API | [remove.bg](https://www.remove.bg) |
| **Recraft** | AI 设计工具 | [recraft.ai](https://recraft.ai) |

### 批处理与自动化

| 工具 | 描述 | 链接 |
|:-----|:-----|:-----|
| **Atlas Cloud API** | 46 个模型的统一 API | [atlascloud.ai](https://www.atlascloud.ai?ref=JPM683) |
| **ComfyUI API** | 无头工作流执行 | [文档](https://github.com/comfyanonymous/ComfyUI) |
| **n8n** | 工作流自动化 | [n8n.io](https://n8n.io) |

---

## 💰 定价详解

### 各提供商价格对比

| 提供商 | 模型 | 单图价格 | 速度 | 质量 |
|:-------|:-----|:---------|:-----|:-----|
| **Google** | Nano Banana 2 | $0.072 | ⚡⚡⚡ | ⭐⭐⭐⭐⭐ |
| **Google** | Imagen4 Ultra | ~$0.10+ | ⚡ | ⭐⭐⭐⭐⭐ |
| **Google** | Imagen4 | ~$0.06-0.08 | ⚡⚡ | ⭐⭐⭐⭐ |
| **Google** | Imagen4 Fast | ~$0.04-0.06 | ⚡⚡⚡ | ⭐⭐⭐ |
| **BFL** | Flux Schnell | ~$0.003 | ⚡⚡⚡ | ⭐⭐⭐ |
| **BFL** | Flux Dev | ~$0.03 | ⚡⚡ | ⭐⭐⭐⭐ |
| **字节跳动** | Seedream v5.0 | ~$0.03-0.05 | ⚡⚡ | ⭐⭐⭐⭐ |
| **阿里巴巴** | Qwen-Image Max | ~$0.02-0.04 | ⚡⚡ | ⭐⭐⭐⭐ |
| **阿里巴巴** | Z-Image Turbo | ~$0.01-0.02 | ⚡⚡⚡ | ⭐⭐⭐ |

> 💡 **Atlas Cloud 优势：** 所有模型统一定价 + **首充赠送 25%（最高 $100）**
>
> 👉 [立即开始 atlascloud.ai](https://www.atlascloud.ai?ref=JPM683)

### Atlas Cloud vs fal.ai — 价格对比

| 模型 | fal.ai | Atlas Cloud | 备注 |
|:-----|:-------|:-----------|:-----|
| **Nano Banana 2** | $0.0398/张 | $0.072/张 | fal.ai 单价更低，但 Atlas Cloud 提供所有分辨率至 4K 统一定价 |
| **Flux Kontext Pro** | $0.04/张 | — | fal.ai 上可用 |
| **Seedream V4** | $0.03/张 | $0.032/张 | 价格非常接近 |
| **Flux Dev** | — | $0.012/张 | Atlas Cloud 在 Flux Dev 上极具竞争力 |

> **为什么即使 fal.ai 部分模型更便宜，仍选择 Atlas Cloud？**
> - **统一 API** — 46 个图像模型，一个 API Key、一个端点、一个账单
> - **无审查模式** — 支持模型无内容过滤
> - **批量生成** — 单次请求最多生成 15 张图（Seedream Sequential）
> - **LoRA 支持** — 在所有兼容模型上使用自定义 LoRA
> - **统一定价** — 高分辨率无额外费用

### 成本优化技巧

1. **用 Flux Schnell 打草稿** → 用高端模型最终出图
2. **使用批量模式**（Seedream 序列）处理大量需求
3. **先低分辨率生成** → 用 Real-ESRGAN 放大
4. **缓存提示词** — 复用有效提示词
5. **选对模型** — 不要为 Flux Schnell 就能搞定的任务用 Imagen4 Ultra

---

## ❓ 常见问题

### 2026 年最好的 AI 图片生成器是什么？

取决于你的使用场景。**照片写实**选 **Nano Banana 2** 和 **Imagen4 Ultra**。**速度和成本**选 **Flux Schnell**。**批量生成**选 **Seedream v5.0** 的序列模式（每批 15 张）。**自定义风格**选 **Flux Dev LoRA**。[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683) 让你通过一个 API 使用全部 46 个模型。

### 最便宜的 AI 图片 API 是什么？

**Flux Schnell** 提供最低的单图成本，约 $0.003/张。高质量高性价比选 **Nano Banana 2**，$0.072/张起。通过 [Atlas Cloud](https://www.atlascloud.ai?ref=JPM683) **首充赠送 25%**（最高 $100），更加实惠。

### 如何用 API 生成 AI 图片？

使用 [Atlas Cloud](https://www.atlascloud.ai?ref=JPM683) 等统一 API。注册获取 API Key，然后发送包含提示词和模型选择的 HTTP 请求即可。参见上方[快速开始](#-快速开始--统一-api)部分的 cURL、Python 和 JavaScript 示例。

### Flux vs Nano Banana 2 vs Midjourney — 哪个更好？

| 特性 | Flux Dev | Nano Banana 2 | Midjourney |
|:-----|:---------|:--------------|:-----------|
| API 支持 | ✅ | ✅ | ❌（仅 Discord） |
| 速度 | ⚡⚡ | ⚡⚡⚡ | ⚡⚡ |
| 质量 | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| LoRA | ✅ | ❌ | ❌ |
| 编辑 | ❌（仅 Kontext） | ✅（14 参考图） | 有限 |
| 无审查 | ✅（Atlas） | ❌ | ❌ |
| 价格 | ~$0.03 | $0.072 | $10+/月 |

### 生成 NSFW 内容最好的 AI 图片模型是什么？

[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683) 上的 **Flux Dev** 提供无限制生成，没有内容过滤。大多数其他提供商（Google、字节跳动、阿里巴巴）会应用安全过滤器。

### 可以批量生成图片吗？

可以！**Seedream v5.0**（以及 v4.5、v4）支持**序列模式** — 每次 API 请求生成最多 **15 张图片**。非常适合产品变体、A/B 测试和规模化内容创作。

### 哪个模型的图中文字渲染最好？

**Nano Banana 2** 目前在文字渲染精度方面领先。它能可靠地生成包含可读文字、logo 和排版的图片。

### AI 图片编辑是如何工作的？

**Nano Banana 2 Edit**、**Flux Kontext**、**Seedream Edit** 和 **Wan Edit** 等模型接受输入图片加文字指令。你可以更换背景、添加/移除物体、风格迁移等。Nano Banana 2 Edit 支持最多 **14 张参考图片**。

---

## 🎨 所有 AI 图片模型，一个 API

<div align="center">

**来自 Google、字节跳动、Black Forest Labs 和阿里巴巴的 46 个图片模型。**

全部通过一个统一 API 访问。

| 特性 | 详情 |
|:-----|:-----|
| ✅ **46 个模型** | 所有主流 AI 图片模型 |
| ✅ **无审查** | 支持模型上的完全创作自由 |
| ✅ **低至 $0.072** | 比官方 API 更便宜 |
| ✅ **25% 赠金** | 首充赠送（最高 $100） |
| ✅ **一个 API Key** | 切换模型只需改一个参数 |
| ✅ **批量支持** | 每次请求最多 15 张图片 |

<br/>

### 👉 [立即开始使用 Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)

*首充赠送 25%，最高 $100*

</div>

---

## 📈 Star 历史

<div align="center">

[![Star History Chart](https://api.star-history.com/svg?repos=atlascloud/awesome-ai-image-generation&type=Date)](https://star-history.com/#atlascloud/awesome-ai-image-generation&Date)

**⭐ Star 本仓库，追踪 AI 图片生成最新动态！**

</div>

---

## 🤝 贡献指南

欢迎贡献！请随时提交 Pull Request。

1. Fork 本仓库
2. 创建特性分支（`git checkout -b feature/add-new-model`）
3. 提交更改（`git commit -m '添加新模型章节'`）
4. 推送分支（`git push origin feature/add-new-model`）
5. 发起 Pull Request

**可以贡献的内容：**
- 新模型或模型更新
- 带效果展示的提示词示例
- 工具推荐
- 翻译改进
- 错误修正

---

## 📄 许可证

本项目基于 **MIT 许可证** 开源 — 详见 [LICENSE](LICENSE) 文件。

---

<div align="center">

**由 AI 图片生成社区用 ❤️ 打造**

[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683) · [反馈问题](../../issues) · [功能建议](../../issues)

</div>
