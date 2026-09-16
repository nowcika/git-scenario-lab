# 실전 시나리오 목록

자세한 단계, 문제 해결 가이드, 자동 채점은 [Git 실습실](https://nowcika.github.io/git-lab-practice/#scenarios)에서 확인합니다.

| 번호 | 시작점 | 해결 브랜치 | 핵심 명령 |
|---|---|---|---|
| 01 | `scenario/upstream-update` | `solution/upstream-sync` | `remote`, `fetch`, `merge` |
| 02 | `scenario/conflict-left/right` | `solution/conflict` | conflict 해결, merge commit |
| 03 | 외부 자료 저장소 | `solution/external-remote` | 여러 remote, `git show` |
| 04 | `scenario/revert` | `solution/revert` | `git revert` |
| 05 | `scenario/rebase-topic/base` | `solution/rebase` | `git rebase` |
| 06 | `scenario/reset` | `solution/reset` | `git reset --hard` |
| 07 | `scenario/reflog-base` | `solution/reflog` | `git reflog`, 복구 |
| 08 | `scenario/amend` | `solution/amend` | `git commit --amend` |
| 09 | `scenario/cherry-source` | `solution/cherry-pick` | `git cherry-pick` |
| 10 | `scenario/diff-base/target` | `solution/diff` | `git diff`, patch 분석 |
| 11 | `scenario/show-source` | `solution/show` | `git show`, 커밋 조사 |
| 12 | `scenario/patch-source` | `solution/patch` | `format-patch`, `git am` |
| 13 | `scenario/blame` | `solution/blame` | `git blame`, `git log -p` |
| 14 | `scenario/branch-workflow` | `solution/branch-a/b` | `switch`, commit 이동, amend |
| 15 | 완료 커밋 | `solution-v1.0.0` tag | annotated tag |

## Remote 주소

- 원본(`upstream`): `https://github.com/nowcika/git-scenario-lab.git`
- 외부 자료(`external`): `https://github.com/nowcika/git-scenario-library.git`

`scenario/*` 브랜치는 문제의 시작 상태입니다. 직접 변경하지 말고 지정된 `solution/*` 브랜치를 만들어 해결하세요. reset, amend, rebase는 커밋 SHA를 바꾸거나 이력을 이동하므로 공유 브랜치에서 임의로 실행하지 않습니다.
