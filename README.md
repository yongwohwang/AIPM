# AIPM

AI 기반 프로덕트 매니지먼트(AI Product Management) 프로젝트.

> **상태:** 초기 셋업 단계. 애플리케이션 코드는 아직 없으며, 기술 스택이 확정되지 않았습니다.
> 스택 결정은 [docs/decisions/0001-stack-selection.md](docs/decisions/0001-stack-selection.md) 참고.

## 목표

프로덕트 매니지먼트 업무(요구사항 정리, 이슈 분류·우선순위, 스펙 리뷰, 리서치 요약 등)를
AI로 보조하거나 자동화하는 것을 목표로 합니다.

## 저장소 구조

```
.
├── docs/
│   └── decisions/     # ADR(Architecture Decision Record) — 주요 의사결정 기록
├── src/               # 애플리케이션 소스 (스택 확정 후 추가)
└── tests/             # 테스트 (스택 확정 후 추가)
```

## 시작하기

기술 스택이 확정되면 이 섹션에 설치·실행 방법을 채웁니다.

## 기여

- 작업은 기능 브랜치에서 진행하고 PR로 병합합니다.
- 되돌리기 어려운 구조적 결정은 `docs/decisions/`에 ADR로 남깁니다.
