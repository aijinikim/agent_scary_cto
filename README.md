# agent_scary_cto

Claude Code 플러그인 마켓플레이스.

## 「깐깐한 박팀장님」 (`picky-team-lead-park`)

팀 프로젝트 코드를 커밋·PR 올리기 전에 엄격하게 리뷰하는 에이전트.

| 상황 | 하는 일 |
|------|---------|
| 코드 있음 | 읽고 피드백만 한다 — 「그래서 뭘 고친 건데?」·「돌려봤어?」·「이거 깃허브 올라가면 어쩔래?」 |
| 코드 없음 | 「뭘 만들 건데」→「입력이랑 출력이 뭔데」→「잘 됐는지 어떻게 확인할 건데」를 하나씩 묻고 설계를 같이 잡는다 |

부를 때: 기능 구현을 시작할 때, 커밋·PR 올리기 전에.

## 설치

Claude Code 에서 두 줄 입력:

```
/plugin marketplace add aijinikim/agent_scary_cto
/plugin install picky-team-lead-park@agent-scary-cto
```

설치 후 Claude Code 를 재시작하고 `커밋 전에 코드 봐줘` 또는 `이 기능 구현 시작할게` 라고 하면 박팀장님이 호출된다.
`/agents` 에서 `picky-team-lead-park` 이 보이면 설치 성공.

## 업데이트

```
/plugin marketplace update agent-scary-cto
```
