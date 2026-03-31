# Cursor AI Workshop — 나만의 바이브코딩 4단계

> AI로 기획하고, 만들고, 배포까지 — 3시간 실습 워크숍

## 워크숍 개요

| 항목 | 내용 |
|------|------|
| 소요시간 | 3시간 (180분) |
| 대상 | 주니어 개발자, 비개발자 |
| 핵심 | 실습 중심 — 4개 앱을 직접 만들고 배포 |

## 사전 준비

1. **Cursor 설치**: [cursor.com/download](https://cursor.com/download)
2. **계정 로그인 준비**
3. **Node.js LTS 설치**: [nodejs.org](https://nodejs.org/)
4. **이 저장소 다운로드**:
   ```bash
   git clone https://github.com/NewTurn2017/cursor-ai-workshop.git
   ```
   또는 상단 **Code → Download ZIP** 클릭

## 오늘의 흐름

| 시간 | 구간 | 내용 |
|------|------|------|
| 0:00–0:10 | Intro | AI 시대의 변화, 오늘의 목표 |
| 0:10–0:40 | Setup | Cursor + Node + Git + vibe-skills + GitHub + Vercel |
| 0:40–1:15 | 실습 1 | 내 홈페이지 + Vercel 배포 |
| 1:25–1:55 | 실습 2 | 드래그 칸반보드 + Vercel 배포 |
| 1:55–2:25 | 실습 3 | AI 채팅 앱 (OpenAI API) + Vercel 배포 |
| 2:30–2:50 | 실습 4 | 자유 프로젝트 + 배포 |
| 2:50–3:00 | 마무리 | 리소스 + 다음 주 첫 적용 |

## 실습 가이드

| 실습 | 내용 | 기술 | 가이드 |
|------|------|------|--------|
| 실습 1 | 나를 소개하는 홈페이지 | HTML/CSS/JS | [exercises/01-homepage.md](exercises/01-homepage.md) |
| 실습 2 | 드래그 칸반보드 TODO | React + localStorage | [exercises/02-kanban-board.md](exercises/02-kanban-board.md) |
| 실습 3 | AI 채팅 앱 | Next.js + OpenAI API | [exercises/03-ai-chat.md](exercises/03-ai-chat.md) |
| 실습 4 | 자유 프로젝트 (10개 옵션) | 선택 | [exercises/04-free-project.md](exercises/04-free-project.md) |

## 슬라이드 보기

```bash
cd slides
python3 -m http.server 8000
```
`http://localhost:8000` 접속 | `←` `→` 키로 이동 | `#번호`로 직접 점프

## vibe-skills 설치

**macOS / Linux**
```bash
curl -fsSL https://raw.githubusercontent.com/NewTurn2017/vibe-skills/main/install.sh | bash -s -- --cursor
```

**Windows (PowerShell)**
```powershell
irm https://raw.githubusercontent.com/NewTurn2017/vibe-skills/main/install.ps1 | iex
```

## 핵심 단축키

| 단축키 | 기능 |
|--------|------|
| `⇧⌘L` | New Agent |
| `⌘J` | Terminal |
| `⌘B` | Files 숨기기 |
| `⌘P` | 파일 검색 |
| `⇧⌘B` | Browser |
| `⌥⌘E` | Chat 최대화 |

## 추가 학습 리소스

| 리소스 | 링크 |
|--------|------|
| Cursor 공식 문서 | [docs.cursor.com](https://docs.cursor.com/) |
| Cursor 학습 가이드 | [cursor.com/learn](https://cursor.com/learn) |
| vibe-skills | [vibe.codewithgenie.com](https://vibe.codewithgenie.com) |
| Cursor Changelog | [cursor.com/changelog](https://cursor.com/changelog) |

---

> "기능보다 흐름을, 코드보다 기획을"
