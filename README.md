# 🗺️ K-Vision AI
> 한국관광공사 이미지 데이터로 학습한 **한국형 관광 이미지 생성 AI 모델**

[![Korea Tourism](https://img.shields.io/badge/Data-한국관광콘텐츠랩-0F6E56?style=flat-square)](https://www.visitkorea.or.kr)
[![License](https://img.shields.io/badge/License-공공저작물_자유이용-blue?style=flat-square)]()
[![Status](https://img.shields.io/badge/Status-Beta-orange?style=flat-square)]()

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
| 활용 카테고리 | 자연, 전통 건축, 한식, 축제, 숙박, 도시 야경 |
| 이미지 수 | 약 500장 (Fine-tuning 학습용) |
| 라이선스 | 한국관광공사 공공저작물 자유이용허락 |

---

## ⚙️ 서비스 흐름

```
사용자 키워드 입력  →  K-Vision 모델 추론  →  이미지 생성 & 다운로드
   (지역/테마/계절)         (Fine-tuned)           (JPG / PNG)
```

---

## 🖼️ 생성 결과 예시

> 아래는 K-Vision AI가 생성한 한국 관광 이미지 샘플입니다.

### 경복궁 야경
![경복궁](images/gyeongbokgung.jpg)

### 제주 유채꽃밭
![제주](images/jeju_canola.jpg)

### 전주 한옥마을
![전주](images/jeonju_hanok.jpg)

### 한식 한상차림
![한식](images/korean_food.jpg)

---

## 📈 기대 효과

- 여행 블로그·SNS 제작자가 저작권 걱정 없이 한국 관광 이미지 즉시 생성 가능
- 소규모 관광업체가 별도 촬영 비용 없이 홍보 이미지 제작 가능
- 한국 문화를 정확히 표현한 AI 이미지로 해외 관광객 유입 기여

---

## 🏛️ 데이터 출처 및 라이선스

본 프로젝트는 **한국관광공사 콘텐츠랩**의 공개 이미지 콘텐츠 정책에 따라
적법하게 활용되었습니다.

- 데이터 제공: [한국관광공사 한국관광콘텐츠랩](https://api.visitkorea.or.kr/#/)
- 이용 조건: 공공저작물 자유이용허락 (출처 표시 조건)

---

*본 프로젝트는 한국관광공사 콘텐츠랩 활용사례 이벤트 참여 목적으로 제작되었습니다.*
