# Cursor AI Workshop — 나만의 바이브코딩 4단계

> **리서치 → 계획 → 구현 → 검토** — AI를 잘 쓰는 사람은 기능을 많이 아는 사람이 아니라, 4단계로 일을 굴리는 사람입니다.

## 워크숍 개요

| 항목 | 내용 |
|------|------|
| 소요시간 | 3시간 (180분) |
| 대상 | Cursor를 처음 쓰거나, AI 작업 흐름을 더 또렷하게 잡고 싶은 사람 |
| 핵심 주제 | 나만의 바이브코딩 4단계 — 리서치 → 계획 → 구현 → 검토 |

## 사전 준비

1. **Cursor 설치**: [cursor.com/download](https://cursor.com/download)
2. **계정 로그인 준비**
3. **Node.js LTS 설치**: [nodejs.org](https://nodejs.org/)
4. **이 저장소 다운로드**:
   ```bash
   git clone https://github.com/NewTurn2017/cursor-ai-workshop.git
   ```
   또는 상단 **Code → Download ZIP** 클릭

## 폴더 구조

```
cursor-ai-workshop/
├── slides/              ← 발표 슬라이드 (브라우저에서 열기)
│   ├── index.html
│   └── images/
├── mock-data/           ← 실습용 샘플 데이터
├── docs/                ← 커리큘럼, 퀵스타트, 참고 자료
├── exercises/           ← 실습별 가이드 + 프롬프트 템플릿
└── README.md
```

## 슬라이드 보기

```bash
cd slides
python3 -m http.server 8000
```
브라우저에서 `http://localhost:8000` 접속, 또는 `slides/index.html`을 더블클릭해서 열어도 됩니다.

**조작**: `←` `→` 키로 이동 | 슬라이드 번호 클릭으로 점프

## 오늘 바로 쓰는 4문장

| 단계 | 문장 |
|------|------|
| 리서치 | "먼저 상황을 정리해줘" |
| 계획 | "시작 전에 5줄 계획을 보여줘" |
| 구현 | "이 범위만 만들어줘" |
| 검토 | "바뀐 점과 확인 방법을 알려줘" |

## 핵심 단축키

| 단축키 (macOS / Windows) | 기능 |
|--------------------------|------|
| `Cmd+I` / `Ctrl+I` | Agent |
| `Cmd+L` / `Ctrl+L` | Chat |
| `Cmd+K` / `Ctrl+K` | Inline Edit |
| `Shift+Tab` | Plan Mode |
| `Tab` | 제안 수락 |

## 실습 목록

| 실습 | 내용 | 가이드 |
|------|------|--------|
| 실습 1 | 회의 메모 / 프로젝트 업데이트 정리기 | [exercises/01-meeting-notes.md](exercises/01-meeting-notes.md) |
| 실습 2 | 공지/FAQ 생성기 | [exercises/02-faq-generator.md](exercises/02-faq-generator.md) |
| 실습 3 | 작은 추가 + 짧은 수정 (디버깅) | [exercises/03-debug-review.md](exercises/03-debug-review.md) |
| 실습 4 | 4단계 미니 프로젝트 | [exercises/04-mini-project.md](exercises/04-mini-project.md) |

## 재사용 프롬프트 8선

```text
1) 먼저 상황을 정리해줘.
2) 시작 전에 5줄 계획을 보여줘.
3) 이 범위만 만들어줘.
4) 바뀐 점과 확인 방법을 알려줘.
5) 이 요청을 짧게 요약해줘.
6) 입력값으로 FAQ 초안을 만들어줘.
7) 회의 메모 / 프로젝트 업데이트 summary로 정리해줘.
8) 원인을 먼저 설명한 다음 고쳐줘.
```

## 오늘 지킬 원칙

- 실제 고객정보, 비밀번호, 키는 넣지 않는다.
- 외부 API 대신 mock 데이터를 사용한다.
- 한 번에 크게 시키지 말고 **작은 범위**로 나눈다.
- 결과를 받으면 바로 넘기지 말고 **검토 문장**을 붙인다.

## 추가 학습 리소스

| 리소스 | 링크 |
|--------|------|
| Cursor 공식 문서 | [docs.cursor.com](https://docs.cursor.com/) |
| Cursor 학습 가이드 | [cursor.com/learn](https://cursor.com/learn) |
| Cursor Workshops | [cursor.com/workshops](https://cursor.com/workshops) |
| Cursor Changelog | [cursor.com/changelog](https://cursor.com/changelog) |

## 오늘 끝나기 전에 적기

```
다음 주에 Cursor로 가장 먼저 굴려볼 일:
_______________________________________

그때 먼저 쓸 문장:
_______________________________________
```

---

> "기능보다 흐름을 챙겨가시면 됩니다."
