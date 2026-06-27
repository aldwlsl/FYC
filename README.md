# 🌐 AURORA — Diplomatic Discovery Engine

> "The future of diplomacy is not searched. It is discovered."

**2026년 외교 공공데이터·AI 활용 경진대회 출품작**

## 소개
AURORA는 외교부·KOICA·KF의 공공데이터(26,000+건)를 AI Knowledge Graph로 통합하여, 아직 발견되지 않은 국제협력 기회를 예측하고 UN SDGs 기여도를 자동 매핑하는 Diplomatic Discovery Platform입니다.

## 주요 기능
- 🔮 **Link Prediction** — 국가×분야별 협력 가능성 수치 예측
- 🌐 **Knowledge Graph** — 외교 데이터 네트워크 시각화
- 🌊 **Ripple Effect** — 정책 파급 효과 시뮬레이션
- 🔍 **Evidence Graph** — AI 판단 근거 투명 공개
- 🌍 **SDGs Auto-Tagger** — UN SDGs 17개 목표 자동 매핑

## 활용 데이터
| 기관 | 데이터셋 | 수집량 |
|------|---------|--------|
| KOICA·KF | KOICA-KF 융합 ODA 사업정보 | 14,067건 |
| 외교부 | 재외공관 정보 | 184개 |
| 외교부 | 국가별 관계정보 | 197개국 |
| KF | 한류현황·공공외교 사업 | 12,144건 |

## 실행 방법
```bash
pip install -r requirements.txt
streamlit run app.py
```
