# 실습 3: AI 채팅 앱

> **소요 시간**: 30분
> **기술**: Next.js + Vercel AI SDK + OpenAI API
> **배포**: Vercel

## 기술 용어

- **OpenAI API** — AI 모델을 호출하는 인터페이스
- **API Key** — AI 서비스 이용을 위한 인증 키 (선택)
- **@ai 멘션** — 채팅에서 AI를 호출하는 트리거
- **Vercel AI SDK** — AI 스트리밍 응답을 쉽게 구현하는 라이브러리

## Step 1: 리서치 + 기획

vibe-research로 기술 조사부터 시작합니다:

```text
카카오톡 오픈채팅 스타일의 AI 채팅 앱을 구현하려고 해. 먼저 아래 항목을 조사해줘:

1. OpenAI API 최신 채팅 모델 비교 (가격, 속도, 성능)
2. Vercel AI SDK의 스트리밍 채팅 구현 방식
3. 카카오톡 오픈채팅 UI 핵심 요소 (메시지 버블, 프로필, 시간 표시, 읽음 표시)

조사 결과를 바탕으로 구현 계획을 세워줘.
```

구현 요구사항:

```text
카카오톡 오픈채팅 스타일의 AI 채팅 앱을 구현해줘.
- Next.js + Vercel AI SDK
- 누구나 들어올 수 있는 단체 채팅방 UI
- @ai 멘션 시 AI가 전체 대화 흐름을 읽고 요약/질문 답변
- OpenAI API 연동 (스트리밍 응답)
- 반응형 모바일 대응
```

## Step 2: API Key 설정

OpenAI API Key 발급 (선택사항):
- https://platform.openai.com/api-keys 에서 발급
- API Key가 없어도 UI 구현과 mock 데이터로 실습 가능

```text
.env 파일에 VITE_OPENAI_API_KEY를 설정해줘.
```

## Step 2b: 수정

```text
@ai 멘션 시 타이핑 애니메이션 효과를 추가해줘
```
```text
대화 요약 기능을 버튼 하나로 실행하게 바꿔줘
```
```text
메시지 시간 표시를 카카오톡처럼 오전/오후로 바꿔줘
```
```text
사용자 프로필 아바타를 랜덤 색상으로 생성해줘
```

## Step 3: 배포

```text
이 React 프로젝트를 Vercel로 배포해줘.
환경변수 VITE_OPENAI_API_KEY도 Vercel에 설정해줘.
vercel CLI로 배포하고, 배포된 URL을 알려줘.
```

## 체크리스트

- [ ] 카카오톡 스타일 UI가 보인다
- [ ] 메시지를 입력하고 전송할 수 있다
- [ ] @ai 멘션으로 AI가 응답한다
- [ ] Vercel 배포 URL이 나왔다
