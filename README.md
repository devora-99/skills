# skills

이 저장소는 프로젝트 전용 `gstack` 스킬과 `AGENTS.md` 규칙을 함께 포함합니다.

## 새 PC 사용법

1. 저장소 clone
```bash
git clone https://github.com/wnghks8898-cmd/skills.git
cd skills
```

2. 필요 도구 설치
- Git
- Node.js
- Bun
- Codex

3. 프로젝트 루트에서 setup 실행
```bash
cd .agents/skills/gstack
./setup --host codex
```

4. Codex에서 이 저장소 루트를 열고 새 세션 시작

## 주의

- 항상 저장소 루트를 열어야 `AGENTS.md`와 `.agents/skills` 규칙이 같이 적용됩니다.
- 이 저장소는 생성 산출물을 최소화해서 커밋하고, 필요한 바이너리는 setup으로 다시 만듭니다.
