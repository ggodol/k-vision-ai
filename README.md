# 🗺️ K-Vision AI
> 한국관광공사 이미지 데이터로 학습한 **한국형 관광 이미지 생성 AI 모델**

[![Korea Tourism](https://img.shields.io/badge/Data-한국관광콘텐츠랩-0F6E56?style=flat-square)](https://www.visitkorea.or.kr)
[![License](https://img.shields.io/badge/License-공공저작물_자유이용-blue?style=flat-square)]()
[![API](https://img.shields.io/badge/API_사용-없음-gray?style=flat-square)]()
[![Status](https://img.shields.io/badge/Status-Beta-orange?style=flat-square)]()
[![Demo](https://img.shields.io/badge/🌐_데모_바로가기-k--vision--ai-1D9E75?style=flat-square)](https://ggodol.github.io/k-vision-ai/)

---

## 🌐 서비스 데모

> 아래 링크에서 K-Vision AI 서비스를 직접 체험해보세요.

**👉 [https://ggodol.github.io/k-vision-ai/](https://ggodol.github.io/k-vision-ai/)**

---

## 📌 프로젝트 소개

기존 해외 범용 이미지 생성 AI(Midjourney, DALL-E 등)는 한국 고유의 문화 요소인
한복, 전통 건축, 한식, 지역 축제 등을 부정확하게 표현하는 한계가 있었습니다.

**K-Vision AI**는 한국관광공사 한국관광콘텐츠랩이 제공하는 고품질 관광 이미지를
학습 데이터로 활용하여, 한국적 색감·구도·문화 맥락을 정확히 이해하는
이미지 생성 모델입니다.

---

## 🗂️ 활용 데이터

| 항목 | 내용 |
|------|------|
| 데이터 출처 | 한국관광공사 한국관광콘텐츠랩 관광 이미지 다운로드 |
| 활용 방식 | **이미지 콘텐츠 다운로드만 활용 (OpenAPI 미사용)** |
| 활용 카테고리 | 자연, 전통 건축, 한식, 축제, 숙박, 도시 야경 |
| 학습 이미지 수 | **500장** |
| 라이선스 | 한국관광공사 공공저작물 자유이용허락 |

> ⚠️ **본 프로젝트는 한국관광공사 OpenAPI를 사용하지 않았습니다.**
> 콘텐츠랩에서 제공하는 관광 이미지 파일(500장)을 직접 다운로드하여
> AI 모델 학습 데이터로만 활용하였습니다.

---

## ⚙️ 서비스 흐름

```
사용자 키워드 입력  →  K-Vision 모델 추론  →  이미지 생성 & 다운로드
   (지역/테마/계절)      (이미지 500장 학습)       (JPG / PNG)
```

---

## 🖼️ 생성 결과 예시

> 아래는 K-Vision AI가 생성한 한국 관광 이미지 샘플입니다.

### 경복궁 야경
![경복궁](gyeongbokgung.png)

### 제주 유채꽃밭
![제주](jeju_canola.png)

### 전주 한옥마을
![전주](jeonju_hanok.png)

### 한식 한상차림
![한식](korean_food.png)

---

## 📈 기대 효과

- 여행 블로그·SNS 제작자가 저작권 걱정 없이 한국 관광 이미지 즉시 생성 가능
- 소규모 관광업체가 별도 촬영 비용 없이 홍보 이미지 제작 가능
- 한국 문화를 정확히 표현한 AI 이미지로 해외 관광객 유입 기여

---

## 🏛️ 데이터 출처 및 라이선스

본 프로젝트는 **한국관광공사 콘텐츠랩**의 공개 이미지 콘텐츠 정책에 따라
적법하게 활용되었습니다.

- 데이터 제공: [한국관광공사 한국관광콘텐츠랩](https://www.visitkorea.or.kr)
- 활용 범위: 이미지 파일 다운로드 (500장) — **OpenAPI 미활용**
- 이용 조건: 공공저작물 자유이용허락 (출처 표시 조건)

---

*본 프로젝트는 한국관광공사 콘텐츠랩 활용사례 이벤트 참여 목적으로 제작되었습니다.*
