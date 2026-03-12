<div align="center">

# 🎨 Awesome AI 이미지 생성

### 2026년 AI 이미지 모델 완벽 가이드

[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Models](https://img.shields.io/badge/이미지_모델-46-blue.svg)](https://www.atlascloud.ai?ref=JPM683)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/atlascloud/awesome-ai-image-generation?style=social)](https://github.com/atlascloud/awesome-ai-image-generation)

**AI 이미지 생성 모델, 프롬프트, 도구, 리소스의 엄선된 컬렉션**

**Google Nano Banana 2 · Imagen4 · ByteDance Seedream · Flux · Wan · Qwen-Image** 등 주요 모델 총망라.

[English](README.md) · [简体中文](README_zh-CN.md) · [日本語](README_ja.md) · [한국어](README_ko.md)

---

**⭐ 유용하다면 Star를 눌러주세요 — 더 많은 분들이 발견할 수 있습니다!**

</div>

---

## 🚀 스폰서 — 46개 이미지 모델, 하나의 API

<div align="center">

**[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)** — 모든 주요 AI 이미지 모델의 통합 API.

하나의 API 키. 46개 이미지 모델. Google, ByteDance, Black Forest Labs, Alibaba — 모두 한곳에.

🎁 **첫 충전 시 25% 보너스 (최대 $100)**

[![Atlas Cloud 체험](https://img.shields.io/badge/Atlas_Cloud-무료_크레딧-blue?style=for-the-badge)](https://www.atlascloud.ai?ref=JPM683)

> 🔒 **엔터프라이즈급 보안** — Atlas Cloud는 **SOC I & II 인증** | **HIPAA 준수** | 미국 기반 회사, 99.9% 가동 시간 SLA.

</div>

---

## 📑 목차

- [2026년 AI 이미지 모델 전체 현황](#-2026년-ai-이미지-모델-전체-현황)
- [Google 모델](#-google-모델)
  - [Nano Banana 2](#nano-banana-2)
  - [Imagen4 패밀리](#imagen4-패밀리)
- [ByteDance Seedream](#-bytedance-seedream)
  - [Seedream v5.0 Lite](#seedream-v50-lite)
  - [Seedream v4.5 / v4](#seedream-v45--v4)
- [Black Forest Labs — Flux](#-black-forest-labs--flux)
  - [Flux Dev & Schnell](#flux-dev--schnell)
  - [Flux LoRA](#flux-lora)
  - [Flux Kontext](#flux-kontext)
- [Alibaba 모델](#-alibaba-모델)
  - [Wan 2.6 / 2.5](#wan-26--25)
  - [Qwen-Image](#qwen-image)
  - [Z-Image Turbo](#z-image-turbo)
- [사용 사례별 추천](#-사용-사례별-추천)
- [빠른 시작 — 통합 API](#-빠른-시작--통합-api)
- [프롬프트 엔지니어링 가이드](#-프롬프트-엔지니어링-가이드)
- [프롬프트 컬렉션 (50+)](#-프롬프트-컬렉션-50)
- [도구 & 에코시스템](#-도구--에코시스템)
- [가격 상세](#-가격-상세)
- [자주 묻는 질문](#-자주-묻는-질문)
- [Star 히스토리](#-star-히스토리)
- [기여하기](#-기여하기)
- [라이선스](#-라이선스)

---

## 📊 2026년 AI 이미지 모델 전체 현황

> 2026년 API로 사용 가능한 모든 주요 AI 이미지 모델의 종합 비교.

| 모델 | 제공업체 | 유형 | 최대 해상도 | 속도 | 편집 | LoRA | 배치 | API 가격 |
|:-----|:--------|:-----|:----------|:-----|:-----|:-----|:-----|:---------|
| **Nano Banana 2** | Google | T2I/편집 | 4K | ⚡⚡⚡ | ✅ | ❌ | ❌ | $0.072/회 |
| **Nano Banana 2 Dev** | Google | T2I/편집 | 4K | ⚡⚡⚡ | ✅ | ❌ | ❌ | $0.072/회 |
| **Nano Banana Pro** | Google | T2I/편집 | 4K | ⚡⚡ | ✅ | ❌ | ❌ | 변동 |
| **Nano Banana** | Google | T2I/편집 | 2K | ⚡⚡ | ✅ | ❌ | ❌ | 변동 |
| **Imagen4 Ultra** | Google | T2I | 4K | ⚡ | ❌ | ❌ | ❌ | 높음 |
| **Imagen4** | Google | T2I | 4K | ⚡⚡ | ❌ | ❌ | ❌ | 변동 |
| **Imagen4 Fast** | Google | T2I | 2K | ⚡⚡⚡ | ❌ | ❌ | ❌ | 변동 |
| **Imagen3** | Google | T2I | 2K | ⚡⚡ | ❌ | ❌ | ❌ | 변동 |
| **Imagen3 Fast** | Google | T2I | 2K | ⚡⚡⚡ | ❌ | ❌ | ❌ | 변동 |
| **Seedream v5.0 Lite** | ByteDance | T2I/편집 | 2K | ⚡⚡ | ✅ | ❌ | ✅ 15장 | 변동 |
| **Seedream v4.5** | ByteDance | T2I/편집 | 2K | ⚡⚡ | ✅ | ❌ | ✅ 15장 | 변동 |
| **Seedream v4** | ByteDance | T2I/편집 | 2K | ⚡⚡ | ✅ | ❌ | ✅ 15장 | 변동 |
| **Flux Dev** | BFL | T2I | 2K | ⚡⚡ | ❌ | ✅ | ❌ | 변동 |
| **Flux Schnell** | BFL | T2I | 1K | ⚡⚡⚡ | ❌ | ❌ | ❌ | 최저 |
| **Flux Dev LoRA** | BFL | T2I | 2K | ⚡⚡ | ❌ | ✅ | ❌ | 변동 |
| **Flux Kontext Dev** | BFL | 편집 | 2K | ⚡⚡ | ✅ | ❌ | ❌ | 변동 |
| **Flux Kontext Dev LoRA** | BFL | 편집 | 2K | ⚡⚡ | ✅ | ✅ | ❌ | 변동 |
| **Wan 2.6 T2I** | Alibaba | T2I | 2K | ⚡⚡ | ❌ | ❌ | ❌ | 변동 |
| **Wan 2.6 Edit** | Alibaba | 편집 | 2K | ⚡⚡ | ✅ | ❌ | ❌ | 변동 |
| **Wan 2.5 T2I** | Alibaba | T2I | 2K | ⚡⚡ | ❌ | ❌ | ❌ | 변동 |
| **Wan 2.5 Edit** | Alibaba | 편집 | 2K | ⚡⚡ | ✅ | ❌ | ❌ | 변동 |
| **Qwen-Image Max** | Alibaba | T2I | 2K | ⚡⚡ | ❌ | ❌ | ❌ | 변동 |
| **Qwen-Image Plus** | Alibaba | T2I | 2K | ⚡⚡ | ❌ | ❌ | ❌ | 변동 |
| **Qwen-Image Edit** | Alibaba | 편집 | 2K | ⚡⚡ | ✅ | ❌ | ❌ | 변동 |
| **Qwen-Image Edit Plus** | Alibaba | 편집 | 2K | ⚡⚡ | ✅ | ❌ | ❌ | 변동 |
| **Z-Image Turbo** | Alibaba | T2I | 2K | ⚡⚡⚡ | ❌ | ❌ | ❌ | 변동 |

> 💡 **46개 모델 모두 하나의 API로 사용 가능** — [Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)

---

## 🔷 Google 모델

### Nano Banana 2

> **Google의 최신, 최고속 이미지 생성 모델 (2026).** 초고속 추론으로 포토리얼한 이미지를 생성하고, 최대 14장의 참조 이미지를 활용한 네이티브 편집과 뛰어난 텍스트 렌더링을 제공합니다.

**주요 특징:**
- 🏎️ **최고속 생성** — 대부분의 프롬프트에서 1초 미만 추론
- 🎯 **14장 참조 이미지** — 업계 최고의 이미지 편집 및 스타일 전이
- ✍️ **텍스트 렌더링** — 생성 이미지 내 정확한 문자 배치
- 🖼️ **4K 출력** — 초고해상도
- 💰 **$0.072/요청** — 프리미엄 모델 중 최고의 가성비

**바리에이션:**
| 바리에이션 | 최적 용도 | 편집 | 속도 |
|:----------|:---------|:-----|:-----|
| Nano Banana 2 T2I | 텍스트→이미지 | ❌ | ⚡⚡⚡ |
| Nano Banana 2 Edit | 이미지 편집 | ✅ (14장 참조) | ⚡⚡⚡ |
| Nano Banana 2 Developer T2I | 개발/테스트 | ❌ | ⚡⚡⚡ |
| Nano Banana 2 Developer Edit | 개발/테스트 | ✅ | ⚡⚡⚡ |

**Nano Banana 2 프롬프트 예시:**

```
1. 주근깨가 있는 젊은 여성의 하이퍼리얼리스틱 초상화, 골든아워
   햇빛이 적갈색 머리카락을 투과, 얕은 피사계 심도, Hasselblad
   X2D 촬영, 100mm f/1.4

2. 한밤중 생물발광 해변의 항공 사진, 전기 블루로 빛나는 파도,
   어두운 화산 모래, 조수 웅덩이에 비치는 별, 내셔널 지오그래픽 품질

3. 스팀펑크 카페 인테리어, 벽의 황동 파이프와 기어, 구리 에스프레소
   머신에서 피어오르는 증기, 따뜻한 앰버 조명, 빈티지 가죽 의자,
   초정밀 4K 렌더링

4. 제품 촬영: 대리석 위의 럭셔리 향수 병, 프리즘 빛을 포착하는
   물방울, 어두운 무디한 배경, 상업 광고 품질, 8K 해상도

5. 타이포그래피 디자인: 크롬 액체 금속 글자 "FUTURE"가 네온 도시
   풍경 위에 부유, 젖은 도로의 반사, 사이버펑크 미학, 시네마틱 조명
```

### Imagen4 패밀리

> **Google의 플래그십 이미지 생성 제품군.** 품질/속도 트레이드오프에 따른 3가지 티어.

| 모델 | 품질 | 속도 | 최적 용도 |
|:-----|:-----|:-----|:---------|
| **Imagen4 Ultra** | ⭐⭐⭐⭐⭐ | ⚡ | 최고 품질, 미술, 인쇄 |
| **Imagen4** | ⭐⭐⭐⭐ | ⚡⚡ | 품질과 속도의 균형 |
| **Imagen4 Fast** | ⭐⭐⭐ | ⚡⚡⚡ | 빠른 프로토타이핑 |

**Imagen4 Ultra 프롬프트 예시:**

```
1. 르네상스 양식의 유화로 그린 현대 도시 황혼, 드라마틱한 키아로스쿠로
   조명, 보이는 붓 터치, 금박 액센트, 미술관 품질

2. 나비 날개의 극단적 매크로 사진, 무지개빛 인편이 반사, 이슬방울이
   작은 렌즈 역할, 포커스 스태킹, Nikon Z9 + 105mm 매크로

3. SF 영화 시네마틱 스틸: 외계 행성의 수정 협곡 가장자리에 선
   고독한 우주비행사, 쌍둥이 일몰, 볼류메트릭 포그, IMAX 품질

4. 초정밀 건축 시각화: 미래주의적 일본 사원, 전통 목조 기법과
   파라메트릭 디자인의 융합, 벚꽃, 아침 안개

5. 포토리얼 정물: 황동 망원경, 아스트롤라베, 나침반, 고지도 —
   마호가니 책상 위, 촛불, 페르메이르 스타일 조명, 8K 초정밀
```

---

## 🟢 ByteDance Seedream

### Seedream v5.0 Lite

> **ByteDance의 최신 이미지 모델 (2026).** 프롬프트 준수도 향상, 인체 해부학 개선, 요청당 최대 15장 배치 생성 지원.

**주요 특징:**
- 📦 **배치 15장** — 1회 API 호출로 최대 15개 바리에이션
- ✏️ **편집 + 시퀀셜** — 고급 편집 및 시퀀셜 처리
- 🎨 **중국어 & 영어** — 이중 언어 프롬프트 지원
- ⚡ **빠른 추론** — 대량 생산에 최적화

### Seedream v4.5 / v4

**Seedream v5.0 vs v4.5 비교:**

| 기능 | v5.0 Lite | v4.5 | v4 |
|:-----|:----------|:-----|:---|
| 프롬프트 준수 | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ |
| 인체 해부학 | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ |
| 텍스트 렌더링 | ⭐⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐ |
| 속도 | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| 배치 (시퀀셜) | ✅ 15장 | ✅ 15장 | ✅ 15장 |
| 편집 | ✅ | ✅ | ✅ |

**Seedream v5.0 프롬프트 예시:**

```
1. 생생한 디지털 컬러로 재해석된 중국 수묵화, 안개 낀 산맥,
   흐르는 폭포, 다리 위의 고독한 학자, 전통 구도에 현대적 색상

2. 초현실적 음식 사진: 돈코츠 라멘 한 그릇, 올라오는 김,
   완벽한 반숙 달걀, 차슈, 김, 파, 45도 앵글 촬영

3. 2050년 미래의 상하이 스카이라인, 유기적 형태의 초고층 빌딩
   사이를 비행하는 차량, 홀로그래픽 광고, 보라색과 주황색 석양

4. 패션 에디토리얼: 무한 거울 방에서 아방가르드 기하학적 의상을
   입은 모델, 쿠사마 야요이 인스파이어, 드라마틱 스튜디오 조명

5. 마법의 도서관, 무한히 떠다니는 책장이 하늘로 나선형 확장,
   황금 먼지 입자, 빛나는 룬 문자의 고서, 따뜻한 촛불
```

**시퀀셜 모드 (배치 생성) 활용:**
- 제품 바리에이션 생성 (색상, 각도)
- 스토리보드 시퀀스 제작
- A/B 테스트 구도 비교
- SNS 콘텐츠 대량 제작

---

## ⬛ Black Forest Labs — Flux

### Flux Dev & Schnell

> **오픈소스의 강자.** Flux는 AI 이미지 생성 커뮤니티의 근간이 되었으며, 비할 데 없는 LoRA 에코시스템을 보유.

| 모델 | 속도 | 품질 | 최적 용도 |
|:-----|:-----|:-----|:---------|
| **Flux Dev** | ⚡⚡ | ⭐⭐⭐⭐ | 프로덕션, 품질 중심 |
| **Flux Schnell** | ⚡⚡⚡ | ⭐⭐⭐ | 최고속, 최저가, 프로토타이핑 |

**Flux Dev** 강점:
- 🎭 **커뮤니티 LoRA** — 수천 개의 커뮤니티 학습 스타일
- 🔓 **Atlas Cloud에서 무검열** — 완전한 창작의 자유
- 🎨 **뛰어난 구도** — 강력한 공간 관계 이해
- 📝 **텍스트 렌더링** — 오픈 모델 중 우수

### Flux LoRA

> **커스텀 스타일 생성** — 커뮤니티 학습 LoRA 모델 활용.

인기 LoRA 소스:
- [Civitai](https://civitai.com) — 최대 LoRA 저장소
- [HuggingFace](https://huggingface.co) — 오픈 모델 허브

### Flux Kontext

> **컨텍스트 내 이미지 편집** — 텍스트 지시로 기존 이미지 편집.

**Flux 프롬프트 예시:**

```
1. [Flux Dev] 이중 노출 사진: 늑대의 얼굴과 북방 소나무 숲의
   융합, 달빛, 신비로운 분위기, 파인 아트 포토, 흑백에 미세한 블루 톤

2. [Flux Dev] 아이소메트릭 3D 렌더링: 아늑한 미니어처 아파트,
   작은 램프의 따뜻한 빛, 창가의 식물, 소파에서 자는 고양이,
   복셀 아트 스타일, 틸트시프트, 파스텔 컬러

3. [Flux Schnell] 빠른 컨셉 스케치: 라테 아트를 만드는 로봇
   바리스타, 스팀펑크 카페, 따뜻한 톤, 일러스트 스타일

4. [Flux Kontext] 이미지 편집: 배경을 열대 해변 석양으로 교체,
   피사체는 유지, 자연스러운 조명 일관성 유지

5. [Flux Dev LoRA] 스튜디오 지브리 스타일: 야생화로 뒤덮인 마법의
   떠있는 섬, 고대 석조 유적, 빨간 우산을 든 소녀가 가장자리에 서서,
   발 아래 구름, 따뜻한 오후 햇살
```

---

## 🟡 Alibaba 모델

### Wan 2.6 / 2.5

> **Alibaba의 멀티모달 모델.** 동영상 생성으로 유명하지만 이미지 생성과 편집에서도 뛰어남.

| 모델 | 유형 | 강점 |
|:-----|:-----|:-----|
| **Wan 2.6 T2I** | 텍스트→이미지 | 최신 품질, 최고 프롬프트 추종 |
| **Wan 2.6 Edit** | 이미지 편집 | 고급 편집 기능 |
| **Wan 2.5 T2I** | 텍스트→이미지 | 검증됨, 안정적 |
| **Wan 2.5 Edit** | 이미지 편집 | 신뢰할 수 있는 편집 |

### Qwen-Image

> **Alibaba의 Qwen 기반 이미지 생성 패밀리.** 중국어/영어 이중 언어 지원.

| 모델 | 유형 | 최적 용도 |
|:-----|:-----|:---------|
| **Qwen-Image Max** | T2I | 최고 품질 |
| **Qwen-Image Plus** | T2I | 균형 |
| **Qwen-Image Edit** | 편집 | 기본 편집 |
| **Qwen-Image Edit Plus** | 편집 | 고급 편집 |

### Z-Image Turbo

> **속도 중시 모델** — 저비용으로 빠른 생성.

**Alibaba 모델 프롬프트 예시:**

```
1. [Wan 2.6] 고요한 가을 선 정원, 정갈한 모래 무늬, 이끼 낀 돌,
   석조 수반에 떠 있는 빨간 단풍잎 한 장, 대나무 사이로 스며드는
   부드러운 아침 빛

2. [Qwen-Image Max] 화려한 중국 설날 축제, 전통 용춤, 고대 거리를
   장식하는 빨간 등, 탑 위로 올라가는 불꽃놀이, 축제 분위기의 군중

3. [Wan 2.6 Edit] 낮의 도시 풍경을 사이버펑크 야경으로 변환,
   네온 간판, 홀로그래픽 빌보드, 빗물에 반사되는 거리

4. [Qwen-Image Plus] 유럽 마을 시장의 수채화 일러스트, 신선한 농산물
   노점, 조약돌 거리, 아침 안개, 따뜻한 황금빛

5. [Z-Image Turbo] 제품 사진: 깨끗한 흰색 위의 미니멀 무선 이어버드,
   부드러운 스튜디오 조명, 약간의 반사, Apple 스타일 상업 사진
```

---

## 🎯 사용 사례별 추천

| 사용 사례 | 추천 모델 | 이유 | 예상 가격 |
|:---------|:---------|:-----|:---------|
| ⚡ 속도 / 프로토타입 | **Flux Schnell** | 최고속, 1초 미만 | 최저 |
| 📷 포토리얼리즘 | **Nano Banana 2** | 가장 사실적, 4K | $0.072/회 |
| 🏆 최고 품질 | **Imagen4 Ultra** | 최고의 디테일 | 높음 |
| 📦 배치 생성 | **Seedream v5.0** | 배치당 15장 | 변동 |
| 🎨 커스텀 스타일 | **Flux Dev LoRA** | 수천 개의 커뮤니티 LoRA | 변동 |
| ✏️ 이미지 편집 | **Nano Banana 2 Edit** | 14장 참조 이미지 지원 | $0.072/회 |
| 💰 예산 절약 | **Flux Schnell** | 최저 이미지 단가 | 최저 |
| 🔓 무검열 / NSFW | **Flux Dev** (Atlas) | 콘텐츠 필터 없음 | 변동 |
| 📝 이미지 내 텍스트 | **Nano Banana 2** | 최고 텍스트 정확도 | $0.072/회 |
| 🏢 엔터프라이즈 | **Imagen4** | Google 품질, 높은 신뢰성 | 변동 |

---

## ⚡ 빠른 시작 — 통합 API

> **하나의 API, 46개 모델 전부.** 파라미터 하나만 바꾸면 모델 전환.

### cURL

```bash
# 텍스트에서 이미지 생성 — Nano Banana 2
curl -X POST "https://api.atlascloud.ai/v1/images/generations" \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "model": "nano-banana-2",
    "prompt": "하이퍼리얼 초상화, 골든아워 조명, 얕은 피사계 심도",
    "size": "1024x1024",
    "n": 1
  }'
```

### Python

```python
# Atlas Cloud 통합 API로 이미지 생성
import requests

API_KEY = "YOUR_API_KEY"
BASE_URL = "https://api.atlascloud.ai/v1"

def generate_image(prompt, model="nano-banana-2", size="1024x1024"):
    """
    통합 API로 이미지 생성.
    46개 모델 모두 지원, model 파라미터만 변경.
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

# 다양한 모델로 생성 — model 파라미터만 변경
result_nb2 = generate_image(
    "장엄한 산의 일몰",
    model="nano-banana-2"        # Google 최신 모델
)

result_flux = generate_image(
    "장엄한 산의 일몰",
    model="flux-dev"             # Flux 오픈소스 모델
)

result_seedream = generate_image(
    "장엄한 산의 일몰",
    model="seedream-v5-lite"     # ByteDance 최신 모델
)

# 결과 출력
print(result_nb2)
```

### JavaScript / Node.js

```javascript
// Atlas Cloud 통합 API로 이미지 생성
const API_KEY = "YOUR_API_KEY";
const BASE_URL = "https://api.atlascloud.ai/v1";

/**
 * 이미지 생성 — 46개 모델 모두 지원
 * @param {string} prompt - 이미지 설명
 * @param {string} model - 모델 이름
 * @param {string} size - 출력 크기
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

// 사용 예시
(async () => {
  const result = await generateImage(
    "사이버펑크 야경 도시, 네온 조명, 비",
    "nano-banana-2"
  );
  console.log("생성 결과:", result);
})();
```

> 📖 전체 API 문서: [Atlas Cloud Docs](https://www.atlascloud.ai?ref=JPM683)

---

## 🧠 프롬프트 엔지니어링 가이드

### 기본 원칙

우수한 프롬프트의 구조:

```
[주제] + [스타일/매체] + [구도] + [조명] + [품질 수식어]
```

**1. 주제 — 구체적으로**
| 약함 ❌ | 강함 ✅ |
|:-------|:-------|
| 여자 | 짧은 머리의 25세 동아시아 여성 |
| 도시 | 새벽 2시, 비에 젖은 도쿄 골목 |
| 꽃 | 아침 이슬이 맺힌 흰 모란 한 송이 |

**2. 스타일 & 매체 키워드**

| 카테고리 | 키워드 |
|:--------|:-------|
| 사진 | DSLR, 필름 사진, 폴라로이드, 항공 촬영, 매크로, 틸트시프트 |
| 디지털 | 컨셉 아트, 디지털 페인팅, 3D 렌더링, CGI |
| 전통 예술 | 유화, 수채화, 수묵화, 목탄, 연필 스케치 |
| 일러스트 | 벡터 아트, 플랫 디자인, 아이소메트릭, 라인 아트 |
| 특정 스타일 | 지브리, 아르누보, 바우하우스, 베이퍼웨이브 |

**3. 구도 테크닉**

| 테크닉 | 설명 | 예시 |
|:-------|:-----|:-----|
| 삼분할법 | 주제를 중앙에서 벗어나게 | "우측 삼분의 일에 배치" |
| 리딩 라인 | 시선을 유도하는 선 | "지평선으로 이어지는 철로" |
| 대칭 | 좌우 대칭 구도 | "완벽하게 대칭인 사원 입구" |
| 프레임 속 프레임 | 자연스러운 프레이밍 | "돌 아치 너머로 보는" |
| 조감도 | 위에서 내려다보는 시점 | "정원의 항공 조감 샷" |

**4. 조명 어휘**

| 조명 | 효과 | 최적 용도 |
|:-----|:-----|:---------|
| 골든아워 | 따뜻하고 부드러운 빛 | 초상화, 풍경 |
| 블루아워 | 차갑고 몽환적 | 도시 풍경 |
| 렘브란트 조명 | 볼에 드라마틱한 삼각형 | 초상화 |
| 림 라이팅 | 빛나는 테두리 | 실루엣 |
| 볼류메트릭 | 보이는 광선 줄기 | 판타지 |
| 키아로스쿠로 | 강한 명암 대비 | 파인 아트 |
| 네온 조명 | 컬러풀한 인공 빛 | 사이버펑크 |

**5. 품질 & 해상도 수식어**

```
초정밀, 8K 해상도, 고해상, 걸작 품질, 프로페셔널 사진,
수상작, 샤프 포커스, 정밀한 디테일, 볼류메트릭 렌더링,
레이 트레이싱
```

### 모델별 팁

**Nano Banana 2:**
- 카메라/렌즈 사양이 효과적 (예: "Sony A7R V, 85mm f/1.2로 촬영")
- 텍스트 생성: 원하는 텍스트를 따옴표로 감싸기
- 참조 이미지로 일관성 대폭 향상

**Seedream v5.0:**
- 중국어 프롬프트 네이티브 지원
- 시퀀셜 모드: 번호 목록으로 바리에이션 기술
- 아시아 미학과 문화 요소에 강함

**Flux Dev:**
- 길고 상세한 프롬프트가 더 좋은 결과
- LoRA 트리거 워드를 프롬프트에 포함해야 함
- 키워드 나열보다 자연어가 효과적

---

## 🎁 프롬프트 컬렉션 (50+)

### 📷 포토리얼

```
1. 일본 노어부의 하이퍼리얼 클로즈업, 수십 년의 바다 이야기를
   말해주는 깊은 주름, 백발의 수염, 풍화된 어부 모자, 골든아워
   빛이 얼굴에, 바다와 배의 보케 배경, Canon EOS R5, 135mm f/2, 8K
   → 추천: Nano Banana 2 | Imagen4 Ultra

2. 가을 노르웨이 피오르드 항공 사진, 에메랄드빛 물에 주황색과
   빨간색 산이 반사, 해안가의 작은 빨간 오두막, 수면 위 아침 안개
   → 추천: Imagen4 Ultra | Nano Banana 2

3. 서울 비 오는 밤의 스트리트 포토, 젖은 도로에 반사된 네온 간판,
   투명 우산을 든 외로운 인물, 얕은 피사계 심도, Leica M11
   → 추천: Nano Banana 2 | Flux Dev

4. 이슬 맺힌 장미 꽃잎 위 깡충거미의 매크로 사진, 무지개빛
   킬리세라, 8개의 눈에 비친 사진작가, 극단적 디테일
   → 추천: Imagen4 Ultra

5. 북유럽 미니멀리스트 주택 포토리얼 인테리어, 눈 덮인 숲을 내다보는
   바닥부터 천장까지 창문, 따뜻한 나무 톤, 임스 라운지 체어, 벽난로
   → 추천: Nano Banana 2 | Seedream v5.0
```

### 🎨 디지털 아트

```
6. 폐허가 된 대성당을 관통해 자라는 거대한 고목, 돌기둥을 감싸는
   뿌리, 스테인드 글라스를 통과하는 다채로운 빛, 이끼와 고사리
   → 추천: Flux Dev | Imagen4

7. 도쿄 옥상에 선 사이버펑크 사무라이, 네온 도시 조명을 반사하는
   카타나, 서보가 보이는 기계 팔, 홀로그래픽 HUD 바이저, 비
   → 추천: Flux Dev | Seedream v5.0

8. 생물발광 건축의 해저 문명, 해파리 모양 건물, 물고기 떼가
   교통, 산호로 덮인 다리, 심해 블루 그라데이션
   → 추천: Imagen4 Ultra | Flux Dev

9. 아늑한 마녀의 오두막, 선반에서 부글거리는 물약, 마법 책 더미
   위의 검은 고양이, 천장에서 말리는 허브, 벽난로 빛
   → 추천: Flux Dev LoRA | Seedream v5.0

10. 구름 위 스팀펑크 비행선 도킹 스테이션, 황동과 구리 건축,
    거대 프로펠러, 빅토리아풍 승객들
    → 추천: Imagen4 Ultra | Flux Dev
```

### 📦 제품 사진

```
11. 공중에 떠있는 럭셔리 기계식 시계, 주변에 흩어진 시계 부품,
    다크 그라데이션 배경, 드라마틱 림 라이트, 8K
    → 추천: Nano Banana 2 | Imagen4

12. 러스틱 나무 테이블 위의 세라믹 커피 머그, 정교한 라떼 아트,
    창문으로 들어오는 아침 햇살, 흐린 베이커리 배경
    → 추천: Seedream v5.0 | Nano Banana 2

13. 대리석 위 스킨케어 보틀 플랫레이, 유칼립투스 잎, 물방울,
    위에서 부드러운 확산광, 클린 미니멀 미학
    → 추천: Nano Banana 2 | Qwen-Image Max

14. 러닝화가 물웅덩이에 스플래시, 프리즈프레임 물 역학, 도시
    환경, 드라마틱 로우 앵글, 나이키 스타일 상업 사진
    → 추천: Nano Banana 2 | Imagen4

15. 미니멀 테크 제품: 깨끗한 흰 면 위 무선 이어버드 케이스,
    소프트 그라데이션 그림자, Apple 스타일, 완벽한 대칭
    → 추천: Z-Image Turbo | Nano Banana 2
```

### 🌸 애니메이션 & 만화

```
16. 벚꽃 정원의 정교한 애니메이션 소녀, 부드러운 핑크 꽃잎 흩날림,
    전통 기모노에 모던 스니커즈, 따뜻한 봄 햇살, 지브리 컬러 팔레트
    → 추천: Flux Dev LoRA | Seedream v5.0

17. 홀로그래픽 디스플레이가 가득한 콕핏의 메카 파일럿, 바이저에
    반사된 우주 전투, 건담 인스파이어, 선라이즈 품질
    → 추천: Flux Dev LoRA | Seedream v5.0

18. 일상 씬: 밤의 따뜻한 라멘집, 노란 빛, 올라오는 김, 장인
    정신의 노인 요리사, 정밀한 음식 일러스트, 신카이 마코토 조명
    → 추천: Flux Dev LoRA | Seedream v5.0

19. 마법 소녀 변신 시퀀스 프리즈프레임, 빛의 리본이 소용돌이,
    다이나믹 포즈, 반짝이는 별 이펙트, 생생한 색채
    → 추천: Flux Dev LoRA

20. 애니메이션 풍경: 사슬로 지면과 연결된 부유섬, 구름 속으로
    떨어지는 폭포, 덩굴에 덮인 고대 유적, 지브리적 세계관
    → 추천: Flux Dev LoRA | Seedream v5.0
```

### 🐉 판타지

```
21. 산 정상에 앉은 고대 드래곤, 오로라를 반사하는 비늘, 숨결에서
    형성되는 얼음 결정, 정교한 날개막 디테일, 에픽 판타지
    → 추천: Imagen4 Ultra | Flux Dev

22. 요정 나라 경계의 버섯 숲, 거대한 생물발광 버섯, 줄기에 새겨진
    작은 요정 집, 반딧불이, 마법의 분위기
    → 추천: Flux Dev | Seedream v5.0

23. 중세 연금술사의 연구실, 유리 기구에서 부글거리는 조합물,
    신비한 기호의 고서, 기계식 아스트롤라베, 촛불과 녹색 마법 빛
    → 추천: Imagen4 | Flux Dev

24. 화려한 다크 아머의 전사 여왕이 불타는 도시 앞에, 망토가
    펄럭임, 룬이 빛나는 전설의 검, 배경의 에픽 전투
    → 추천: Imagen4 Ultra | Flux Dev

25. 수정과 얼음으로 된 마법의 겨울 숲, 머리 위 오로라, 파란
    빛나는 눈의 흰 여우, 빛을 포착하는 눈 입자
    → 추천: Imagen4 Ultra | Nano Banana 2
```

### 🚀 SF

```
26. 열대 섬에서 궤도까지 뻗은 우주 엘리베이터, 보이는 지구 곡률,
    상승하는 화물 포드, 중간부의 구름층, 하드 SF
    → 추천: Imagen4 Ultra | Flux Dev

27. 버려진 세대 우주선 내부, 외계 식물로 뒤덮인, 망가진 크라이오
    포드, 깜빡이는 비상등, 아름다운 퇴폐의 분위기
    → 추천: Flux Dev | Imagen4

28. 사이버네틱 신경 인터페이스 장착, 목 뒤 클로즈업, 보이는
    나노봇, 수술적 정밀함, 블루 홀로그램 가이드
    → 추천: Nano Banana 2 | Imagen4

29. 테라포밍된 화성 식민지, 지평선의 붉은 모래 폭풍, 내부에
    녹색 정원이 보이는 바이오돔, 태양 패널, 하늘의 여러 달
    → 추천: Imagen4 Ultra | Seedream v5.0

30. 양자 컴퓨터 코어 룸, 초저온 챔버에서 빛나는 부유 큐비트,
    케이블의 서리, 청보라색 빛, 깨끗한 미래 건축
    → 추천: Nano Banana 2 | Imagen4
```

### 🏞️ 풍경 & 자연

```
31. 완벽하게 고요한 고산 호수에 걸린 은하수, 별의 반사가 거울
    이미지, 소나무 실루엣, 해안의 생물발광 플랑크톤, 장시간 노출, 8K
    → 추천: Imagen4 Ultra | Nano Banana 2

32. 프로방스 라벤더 밭 일출 드론 샷, 완벽하게 평행한 줄이 기하학
    패턴, 계곡의 아침 안개, 보라색과 금색 팔레트
    → 추천: Nano Banana 2 | Seedream v5.0

33. 아침 안개의 고대 레드우드 숲, 수관을 통과하는 갓 레이,
    고사리가 깔린 숲바닥, 작은 인물로 느끼는 거대한 스케일
    → 추천: Imagen4 Ultra | Nano Banana 2

34. 밤의 화산 폭발, 바다로 흐르는 용암이 거대한 증기 구름 생성,
    화산 연기 속 번개, 장시간 노출, 드라마틱 자연 사진
    → 추천: Imagen4 Ultra

35. 일본 가을 풍경: 잉어 연못 위 전통 빨간 다리, 완벽하게 손질된
    단풍 나무, 잔물결을 만드는 가는 비, 탑의 반사
    → 추천: Nano Banana 2 | Seedream v5.0
```

---

## 🛠️ 도구 & 에코시스템

### 워크플로 & UI 도구

| 도구 | 설명 | 링크 |
|:-----|:-----|:-----|
| **ComfyUI** | 노드 기반 워크플로 에디터 | [GitHub](https://github.com/comfyanonymous/ComfyUI) |
| **Automatic1111** | 인기 Stable Diffusion Web UI | [GitHub](https://github.com/AUTOMATIC1111/stable-diffusion-webui) |
| **Fooocus** | Midjourney 스타일 간소화 UI | [GitHub](https://github.com/lllyasviel/Fooocus) |
| **InvokeAI** | 프로페셔널 크리에이티브 AI 툴킷 | [GitHub](https://github.com/invoke-ai/InvokeAI) |

### LoRA & 모델 저장소

| 플랫폼 | 설명 | 링크 |
|:-------|:-----|:-----|
| **Civitai** | 최대 커뮤니티 모델 저장소 | [civitai.com](https://civitai.com) |
| **HuggingFace** | 오픈 모델 허브 | [huggingface.co](https://huggingface.co) |
| **Tensor.Art** | AI 아트 플랫폼 | [tensor.art](https://tensor.art) |

### 업스케일러 & 후처리

| 도구 | 설명 | 링크 |
|:-----|:-----|:-----|
| **Real-ESRGAN** | 최첨단 이미지 업스케일링 | [GitHub](https://github.com/xinntao/Real-ESRGAN) |
| **Topaz Gigapixel** | 상용 AI 업스케일러 | [topazlabs.com](https://www.topazlabs.com) |
| **CodeFormer** | 얼굴 복원 및 향상 | [GitHub](https://github.com/sczhou/CodeFormer) |

---

## 💰 가격 상세

### 제공업체별 가격 비교

| 제공업체 | 모델 | 이미지 단가 | 속도 | 품질 |
|:--------|:-----|:----------|:-----|:-----|
| **Google** | Nano Banana 2 | $0.072 | ⚡⚡⚡ | ⭐⭐⭐⭐⭐ |
| **Google** | Imagen4 Ultra | ~$0.10+ | ⚡ | ⭐⭐⭐⭐⭐ |
| **Google** | Imagen4 | ~$0.06-0.08 | ⚡⚡ | ⭐⭐⭐⭐ |
| **Google** | Imagen4 Fast | ~$0.04-0.06 | ⚡⚡⚡ | ⭐⭐⭐ |
| **BFL** | Flux Schnell | ~$0.003 | ⚡⚡⚡ | ⭐⭐⭐ |
| **BFL** | Flux Dev | ~$0.03 | ⚡⚡ | ⭐⭐⭐⭐ |
| **ByteDance** | Seedream v5.0 | ~$0.03-0.05 | ⚡⚡ | ⭐⭐⭐⭐ |
| **Alibaba** | Qwen-Image Max | ~$0.02-0.04 | ⚡⚡ | ⭐⭐⭐⭐ |
| **Alibaba** | Z-Image Turbo | ~$0.01-0.02 | ⚡⚡⚡ | ⭐⭐⭐ |

> 💡 **Atlas Cloud 장점:** 모든 모델 경쟁력 있는 가격 + **첫 충전 25% 보너스 (최대 $100)**
>
> 👉 [atlascloud.ai에서 시작하기](https://www.atlascloud.ai?ref=JPM683)

### Atlas Cloud vs fal.ai — 가격 비교

| 모델 | fal.ai | Atlas Cloud | 비고 |
|:-----|:-------|:-----------|:-----|
| **Nano Banana 2** | $0.0398/장 | $0.072/장 | fal.ai가 장당 저렴하지만, Atlas Cloud는 4K까지 모든 해상도 정액제 |
| **Flux Kontext Pro** | $0.04/장 | — | fal.ai에서 이용 가능 |
| **Seedream V4** | $0.03/장 | $0.032/장 | 매우 유사한 가격 |
| **Flux Dev** | — | $0.012/장 | Atlas Cloud가 Flux Dev에서 매우 경쟁력 있음 |

> **fal.ai가 일부 모델에서 더 저렴한데도 Atlas Cloud를 선택하는 이유는?**
> - **통합 API** — 46개 이미지 모델을 하나의 API 키, 하나의 엔드포인트, 하나의 청구서로
> - **무검열 모드** — 지원 모델에서 콘텐츠 필터링 없음
> - **배치 생성** — 요청당 최대 15장 생성 (Seedream Sequential)
> - **LoRA 지원** — 호환 모델 전체에서 커스텀 LoRA 사용
> - **정액제** — 고해상도에서도 추가 비용 없음

### 비용 최적화 팁

1. **Flux Schnell로 초안** → 프리미엄 모델로 최종 작업
2. **배치 모드 활용** (Seedream 시퀀셜)
3. **저해상도로 생성** → Real-ESRGAN으로 업스케일
4. **프롬프트 캐시** — 효과적인 프롬프트 재사용
5. **적절한 모델 선택** — Flux Schnell로 충분한 곳에 Imagen4 Ultra 불필요

---

## ❓ 자주 묻는 질문

### 2026년 최고의 AI 이미지 생성 도구는?

용도에 따라 다릅니다. **포토리얼리즘**은 **Nano Banana 2**와 **Imagen4 Ultra**. **속도와 비용**은 **Flux Schnell**. **배치 생성**은 **Seedream v5.0** (15장/배치). **커스텀 스타일**은 **Flux Dev LoRA**. [Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)에서 46개 모델 모두 하나의 API로 사용 가능.

### 가장 저렴한 AI 이미지 API는?

**Flux Schnell**이 약 $0.003/장으로 최저가. 고품질 가성비는 **Nano Banana 2**가 $0.072/회. [Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)의 **첫 충전 25% 보너스** (최대 $100)로 더 저렴하게.

### API로 AI 이미지를 생성하려면?

[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683) 같은 통합 API를 사용. 가입하고 API 키를 받은 후, 프롬프트와 모델을 포함한 HTTP 요청을 보내면 됩니다. 위의 [빠른 시작](#-빠른-시작--통합-api) 섹션 참조.

### Flux vs Nano Banana 2 vs Midjourney — 어떤 게 더 좋은가?

| 기능 | Flux Dev | Nano Banana 2 | Midjourney |
|:-----|:---------|:--------------|:-----------|
| API 지원 | ✅ | ✅ | ❌ (Discord만) |
| 속도 | ⚡⚡ | ⚡⚡⚡ | ⚡⚡ |
| 품질 | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ |
| LoRA | ✅ | ❌ | ❌ |
| 편집 | ❌ (Kontext만) | ✅ (14 참조) | 제한적 |
| 무검열 | ✅ (Atlas) | ❌ | ❌ |
| 가격 | ~$0.03 | $0.072 | $10+/월 |

### NSFW 콘텐츠에 최적인 AI 이미지 모델은?

[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683)의 **Flux Dev**가 콘텐츠 필터 없이 무제한 생성 가능. 다른 제공업체 (Google, ByteDance, Alibaba)는 안전 필터 적용.

### 배치로 이미지 생성할 수 있나요?

네! **Seedream v5.0** (v4.5, v4도)가 시퀀셜 모드로 요청당 최대 **15장** 생성 가능.

### 이미지 내 텍스트 렌더링이 가장 정확한 모델은?

**Nano Banana 2**가 텍스트 렌더링 정확도에서 선두. 읽을 수 있는 텍스트, 로고, 타이포그래피를 포함한 이미지를 안정적으로 생성.

---

## 🎨 모든 AI 이미지 모델, 하나의 API

<div align="center">

**Google, ByteDance, Black Forest Labs, Alibaba의 46개 이미지 모델.**

모두 하나의 통합 API로.

| 특징 | 상세 |
|:-----|:-----|
| ✅ **46개 모델** | 모든 주요 AI 이미지 모델 |
| ✅ **무검열** | 지원 모델에서 완전한 창작의 자유 |
| ✅ **$0.072부터** | 공식 API보다 저렴 |
| ✅ **25% 보너스** | 첫 충전 시 (최대 $100) |
| ✅ **하나의 API 키** | 파라미터 변경으로 모델 전환 |
| ✅ **배치 지원** | 요청당 최대 15장 |

<br/>

### 👉 [Atlas Cloud에서 생성 시작하기](https://www.atlascloud.ai?ref=JPM683)

*첫 충전 25% 보너스, 최대 $100*

</div>

---

## 📈 Star 히스토리

<div align="center">

[![Star History Chart](https://api.star-history.com/svg?repos=atlascloud/awesome-ai-image-generation&type=Date)](https://star-history.com/#atlascloud/awesome-ai-image-generation&Date)

**⭐ Star를 눌러 AI 이미지 생성 최신 정보를 받아보세요!**

</div>

---

## 🤝 기여하기

기여를 환영합니다! Pull Request를 자유롭게 제출해주세요.

1. 저장소 Fork
2. 피처 브랜치 생성 (`git checkout -b feature/add-new-model`)
3. 변경사항 커밋 (`git commit -m '새 모델 섹션 추가'`)
4. 브랜치 Push (`git push origin feature/add-new-model`)
5. Pull Request 생성

**기여할 수 있는 내용:**
- 새 모델 또는 모델 업데이트
- 결과가 포함된 프롬프트 예시
- 도구 추천
- 번역 개선
- 버그 수정

---

## 📄 라이선스

이 프로젝트는 **MIT 라이선스**에 따라 배포됩니다 — [LICENSE](LICENSE) 파일을 참조하세요.

---

<div align="center">

**AI 이미지 생성 커뮤니티가 ❤️으로 제작**

[Atlas Cloud](https://www.atlascloud.ai?ref=JPM683) · [이슈 보고](../../issues) · [기능 요청](../../issues)

</div>
