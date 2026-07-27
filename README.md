<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/logo/amcg-logo-white.png">
  <img src="assets/logo/amcg-logo.png" alt="AMCG" width="280">
</picture>

# AMCG Brand Font

**AMCG 공식 브랜드 서체**

[![Version](https://img.shields.io/badge/version-1.0.0-FF6C00.svg)](../../releases/latest)
![Platform](https://img.shields.io/badge/platform-Windows_·_macOS_·_Web-002160.svg)
![Weights](https://img.shields.io/badge/weights-9-002160.svg)

</div>

---

AMCG의 공식 브랜드 서체입니다. 국·영문이 함께 쓰이는 문서와 화면에서 일관된 타이포그래피를 유지하도록 설계되었습니다.

## 서체 구성

| Family | 용도 | 특징 |
|--------|------|------|
| **AMCG** | 본문 (국·영문 혼합) | 영문·숫자를 국문보다 약간 크게 조정 |
| **AMCG Display** | 제목·큰 글씨 | 큰 크기에서 영문을 더 강조 |
| **AMCG EN** | 영문 전용 | 영문 본래 크기 |

각 패밀리 **9 weight** — Thin · ExtraLight · Light · Regular · Medium · SemiBold · Bold · ExtraBold · Black

## 다운로드 · 설치

최신 버전은 **[Releases](../../releases/latest)** 에서 받을 수 있습니다.

| 플랫폼 | 파일 |
|--------|------|
| **Windows** | `AMCG-Font-Installer.exe` |
| **macOS** | `AMCG-Font-Installer.pkg` |
| **수동 설치 (TTF)** | `AMCG-Desktop-Fonts.zip` |

설치 후 실행 중인 프로그램(Office 등)은 다시 실행해야 서체 목록에 나타납니다.

## 웹에서 사용

`fonts/web/` 의 woff2 와 `amcg.css` 를 배포한 뒤:

```html
<link rel="stylesheet" href="/assets/amcg.css">
```
```css
body   { font-family: 'AMCG', sans-serif; }         /* 본문 */
h1, h2 { font-family: 'AMCG Display', sans-serif; } /* 제목 */
.latin { font-family: 'AMCG EN', sans-serif; }      /* 영문 전용 */
```

## 타이포그래피 가이드

<div align="center">
<img src="docs/amcg-weight-size-spec.jpg" alt="Weight & size guide" width="720">
</div>

- **크기별 영문 조정** — 혼합 조판 시 영문을 국문보다 크게: 10pt 이하 +0.5pt (`AMCG`), 14pt 이상 +1.0pt (`AMCG Display`)
- **굵기 페어링** — 영문은 국문보다 한 단계 가벼운 굵기로 짝지어 시각적 무게를 맞춤

## 라이선스

[SIL Open Font License 1.1](https://scripts.sil.org/OFL). 본 서체는 Noto Sans KR 및 Outfit 를 사용하여 제작되었습니다. 전체 고지는 [`LICENSE.txt`](LICENSE.txt) 를 참고하세요.

<div align="center">
<sub>© AMCG · Navy <code>#002160</code> · Orange <code>#FF6C00</code></sub>
</div>
