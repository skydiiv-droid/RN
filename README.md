# 간호 지식 저장소 (RN Knowledge Vault)

종합병원 간호 업무용 개인 지식 저장소.
**Claude Code**(수집·정리) → **GitHub**(저장·이력) → **Obsidian**(열람·시각화).

## ⚠️ 원칙

1. **Private 저장소** — 공개하지 않음.
2. **환자 정보(PHI) 절대 금지** — 이름·차트번호 등 개인식별정보는 어떤 노트에도 넣지 않음. "지식 사전"이지 "환자 기록"이 아님.
3. **모든 지식은 참고용** — 최종 판단은 처방·원내 지침·최신 원문. 각 노트 하단에 면책 문구.
4. **폴더는 얕게, 세부 분류는 태그/속성(YAML)으로.**

## 폴더 구조

| 폴더 | 내용 |
|------|------|
| `Diseases` | 질환 (병태·증상·검사·치료·간호) |
| `Drugs` | 의약품 — `성분/` DUR 안전정보 노트 (제품 검색은 검색앱) |
| `Operations` | 수술 |
| `Procedures` | 시술·술기 |
| `Diagnostics` | 진단검사 — `laboratory` / `radiology` / `functional` |
| `Nursing` | 간호 지식·실무지침 |
| `Department Guides` | 진료과별 가이드 |
| `Ward Manual` | 병동 업무·인수인계·프로토콜 |
| `References` | 참고자료 |
| `Templates` | 노트 템플릿 |

## 약품 검색앱

제품 전체(35,206개) 효능·용법·부작용·**DUR(병용금기 등)** 검색:
👉 https://skydiiv-droid.github.io/RN/ (gh-pages 브랜치, 데이터는 여기 vault와 분리)

## 노트 규칙

- 파일명 = 항목명 (예: `타이레놀정500mg.md`)
- 상단 YAML 속성으로 분류, 항목 간 관계는 `[[위키링크]]`로 연결
- 새 노트는 `Templates/` 복사해서 시작
