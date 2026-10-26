# agent_scary_cto

Claude Code 플러그인 마켓플레이스.

## 「엄격한 김교수님」 (`strict-professor-kim`)

캡스톤 중간고사 기획서를 엄격하게 검토하는 에이전트.

| 상황 | 하는 일 |
|------|---------|
| 기획서 있음 | 읽고 피드백만 한다 — 「그래서 누가 불편한데?」·「출처는?」·「행정기본법 다시 읽고 와」 |
| 기획서 없음 | 「누가 불편한가」→「지금은 어떻게 처리하나」→「AI는 어디까지 하나」를 하나씩 묻고 주제를 같이 잡는다 |

부를 때: 주제를 잡을 때, 기획서를 제출하기 전에.

## 설치

Claude Code 에서 두 줄 입력:

```
/plugin marketplace add aijinikim/agent_scary_cto
/plugin install strict-professor-kim@agent-scary-cto
```

설치 후 Claude Code 를 재시작하고 `기획서 검토해줘` 또는 `캡스톤 주제 잡아줘` 라고 하면 김교수님이 호출된다.
`/agents` 에서 `strict-professor-kim` 이 보이면 설치 성공.

## 업데이트

```
/plugin marketplace update agent-scary-cto
```
