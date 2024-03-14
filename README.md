# 주간회고 관리 안내
본 문서는 프로젝트 참여자들이 주간회고를 어떻게 작성하고 관리해야 하는지에 대한 지침을 제공합니다. 주간회고는 자기 성찰과 팀 내 소통을 촉진하는 중요한 과정입니다. 아래의 지침을 따라 주시기 바랍니다.


[주간회고 폴더 구조](#주간회고-폴더-구조)  
[주간회고 파일 작성 방법](#주간회고-파일-작성-방법)  
[주간회고 이슈 연결 및 템플릿 사용](#주간회고-이슈-연결-및-템플릿-사용)  
[주간회고 작성 및 이슈 사용 예시](#주간회고-작성-및-이슈-사용-예시)  
[브랜치 사용 예시](#브랜치-사용-예시)

<br>

## 주간회고 폴더 구조
- 모든 주간회고는 `Retrospectives` 폴더 내에 위치해야 합니다.  
- `Retrospectives` 폴더 내에는 각 참여자의 이름으로 된 폴더를 생성해야 합니다. 예: `Retrospectives/hunsoo/`
- 각 참여자의 폴더 내에는 주간회고 파일을 생성합니다. 파일명은 `YYYY-MM-DD.md` 형식으로 합니다. 예: `2024-03-14.md`

<br>

## 주간회고 파일 작성 방법
1. **폴더 생성**: 본인의 이름으로 된 폴더를 `Retrospectives` 내에 생성합니다. 이미 폴더가 있다면 이 단계를 건너뛰세요.
2. **회고록 파일 생성**: 위의 파일명 규칙(`YYYY-MM-DD.md`)을 따라 주간회고 파일을 생성합니다.
3. **내용 작성**: 주간회고 내용을 Markdown 형식으로 작성합니다. 내용에는 그 주에 배운 점, 성취한 것, 개선할 점 등을 포함할 수 있습니다.

<br>

## 주간회고 이슈 연결 및 템플릿 사용
- 본 프로젝트는 주간회고 이슈 작성을 위한 템플릿을 제공합니다. 매주 GitHub Action을 통해 자동으로 생성되는 주간회고 이슈에서 해당 템플릿을 참고하여 주간회고록을 작성하면 됩니다.
- 본인이 작성한 주간회고록의 GitHub 링크를 해당 주의 주간회고 이슈에 댓글로 남깁니다. 이를 통해 이슈와 회고록을 연결하고, 동료들과 피드백을 주고받을 수 있습니다.
- 이슈 템플릿을 사용함으로써, 모든 참여자가 일관된 형식으로 정보를 제공하고, 효과적으로 소통할 수 있습니다.

<br>

## 주간회고 작성 및 이슈 사용 예시
1. `Retrospectives/hunsoo/2024-03-14.md` 파일을 생성하여 주간회고를 작성합니다.
2. 해당 주의 주간회고 이슈를 확인하고, 이슈 템플릿에 따라 주간회고록을 작성합니다.
3. 작성한 회고록의 GitHub 링크를 해당 이슈에 댓글로 남겨 동료들과 공유합니다.
4. 이슈에서 동료들의 회고록을 읽고, 피드백과 격려의 메시지를 남깁니다.

<br>

## 브랜치 사용 예시
본 프로젝트에서는 main 브랜치에 직접적으로 작업하는 것을 피하고, 각자의 이름으로 된 브랜치에서 작업 후 main으로 병합하는 방식을 권장합니다.

1. **브랜치 생성**: 자신의 이름으로 된 브랜치를 생성합니다. 예: `git branch hunsoo-retrospective`
2. **브랜치로 전환**: 생성한 브랜치로 전환합니다. 예: `git checkout hunsoo-retrospective`
3. **작업 및 커밋**: 브랜치에서 주간회고 작업을 진행하고, 완료 후 변경사항을 커밋합니다.
3. **Pull Request 생성**: 작업이 완료되면, 작업한 브랜치에서 main 브랜치로 Pull Request를 생성합니다. 이때, PR에는 해당 주의 주간회고 이슈 번호를 포함시켜 연결합니다.
4. **코드 리뷰 및 병합**: 팀원들의 리뷰를 받은 후, 문제가 없다면 main 브랜치로 병합합니다.