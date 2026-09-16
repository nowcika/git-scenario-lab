# 실전 시나리오 목록

자세한 단계와 자동 채점은 [Git 실습실](https://nowcika.github.io/git-lab-practice/#scenarios)에서 확인합니다.

| 번호 | 시작 브랜치 | 해결 브랜치 | 목표 |
|---|---|---|---|
| 1 | `main` + `scenario/upstream-update` | `solution/upstream-sync` | upstream 변경 fetch·merge |
| 2 | `scenario/conflict-left` + `scenario/conflict-right` | `solution/conflict` | 같은 파일 충돌 해결과 merge commit |
| 3 | `main` + 외부 저장소 | `solution/external-remote` | 별도 remote의 파일 반영 |
| 4 | `scenario/revert` | `solution/revert` | 잘못된 커밋을 revert로 취소 |
| 5 | `scenario/rebase-topic` + `scenario/rebase-base` | `solution/rebase` | 토픽 커밋 rebase와 선형 이력 |
| 6 | 원하는 완료 커밋 | `solution-v1.0.0` tag | 원격 태그 생성 |

## Remote 주소

- 원본(upstream): `https://github.com/nowcika/git-scenario-lab.git`
- 외부 자료(external): `https://github.com/nowcika/git-scenario-library.git`

`scenario/*` 브랜치는 문제의 시작 상태입니다. 이 브랜치에 직접 push하지 말고 지정된 `solution/*` 브랜치를 새로 만들어 해결하세요.
