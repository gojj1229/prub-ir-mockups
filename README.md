# Prub IR — IT 미션 장표 mockups

Prub IR v6 (IT 별책, 7p)의 두 핵심 페이지 HTML 목업 풀셋.

## 페이지

- [`01_membership_kanpo_search.html`](./01_membership_kanpo_search.html) — 한의사 멤버십 검색 (p3)
- [`02_patient_wiki_3tier.html`](./02_patient_wiki_3tier.html) — 환자 위키 3-Tier 진화 (p4)
- [`index.html`](./index.html) — 랜딩 페이지 (두 mockup 카드 진입점)

## 자산

- `prub_logo.png` — Prub 공용 로고
- `obsidian_graph.png` — 사내 MAGI-wiki Obsidian Graph View 캡처

## 사용 방법

1. 브라우저에서 페이지 열기 (1600px 폭 디자인)
2. Chrome DevTools `Cmd+Shift+P` → "Capture full size screenshot"
3. PNG 추출 후 PPT 16:9 슬라이드에 박제

## 보안

- `<meta name="robots" content="noindex, nofollow, noarchive, nosnippet">` 적용
- `robots.txt`에서 모든 크롤러 차단 (Googlebot, GPTBot, anthropic-ai, ClaudeBot, CCBot 포함)
- 검색엔진/AI 학습 노출 차단

## 후편집

모든 페이지 inline CSS·SVG · 외부 의존성 없음. CSS 변수는 `:root`에 모아둠 (`--orange`, `--navy` 등).

---

INTERNAL ONLY · Prub Inc. · 2026-05-11
