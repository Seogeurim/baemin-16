# Pull Request와 리뷰 참여

## Pull Request란

참고 링크 : [first-contributions](https://github.com/firstcontributions/first-contributions)

Git의 오픈소스들은 어떤 방식으로 contribute & 관리되고 있을까? 보통 다음과 같다.

문제 사항 / 개선 사항 / Bug 등에 대하여 **Issue**를 작성한다. → 해당 repo를 **Fork**한다. → Fork 후 각 repo branch naming convention에 따라 **Branch**를 생성한다. → repo commit convention에 따라 **Commit**하며 필요한 이슈에 대하여 작업한다. → 해당 과정이 끝나면 **Pull Request**를 발행한다. → PR 승인되면 작업 내용을 **Merge**한다.

이러한 플로우를 한 프로젝트에서는 다음과 같이 사용할 수 있다.

구현할 기능에 대하여 **Issue**를 작성한다. → branch naming convention에 따라 **Branch**를 생성한다. → commit convention에 따라 **Commit**하며 맡은 기능을 작업한다. → 해당 과정이 끝나면 **Pull Request**를 발행한다. → 팀원들이 **Code Review**를 진행하여 최대한 품질이 좋은 코드에 대하여 토의한다. → 특정 수의 팀원들이 Approve를 남기면 **Merge**가 가능하다. 이 때, Request Changes 상태가 있다면 무조건 수정되어 해당 상태가 없어져야 **Merge**가 가능하다.

## 그래서 우리는 PR을 통하여

1. 프로젝트에 대하여 팀원들의 작업 현황을 모두 공유한다.
2. PR Review 과정을 통해 서로의 코드에 대한 피드백을 진행하고 코드의 품질을 높인다.

## PR Review Tutorial

### 1. Pull Request 생성하기

PR 내용은 다음과 같은 구조로 확인할 수 있다.

- 최상단 제목 : PR을 작성하게 되면 보통 그 Branch의 이름이 자동으로 제목으로 설정된다. 
- Tab
    - Conversation Tab : 현재 보이는 가장 기본 창 - 대시보드 느낌이다.
    - Commits Tab : 해당 PR의 전체 커밋 로그를 볼 수 있다.
    - Checks Tab : CI/CD 쓸 경우 여기에 표시된다.
    - Files changed Tab : 작성자가 변경한 내용이 보인다. 이 탭에서 리뷰를 진행한다.
- 글 박스 : 작성자가 기존 PR 템플릿에 따라 작성한 내용이 보인다.
- 하단 commits : 커밋 로그들이 보인다.

### 2. Pull Request 리뷰하기

Files changed 탭으로 들어간다.

- 각 파일 별로의 diff를 볼 수 있다.
- 해당 영역을 마우스로 드래그하면 특정 코드에 대한 리뷰를 진행할 수 있다.
- 리뷰를 작성하고 **Start a review** 버튼을 누르면서 여러 개의 리뷰 comment를 남길 수 있다.
- 코드 수정을 구체적으로 제안할 수 있다.

어느 정도 리뷰를 한 다음 가장 오른쪽 상단의 **Finish your review** 버튼을 누르고, 다음의 3가지 선택하면 된다.

- Comment : 이 PR에 나는 comment만 남기겠어.
- Approve : 이 PR 승인하겠어 !!
- Request changes : 내가 요청하는 changes 적용하지 않으면 merge 못해요 !

**Submit review** 버튼을 눌러 리뷰를 등록한다.
