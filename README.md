# Coding_Test
> 토요일 9시마다 푼 문제들을 리뷰한다
> 일주일에 2문제 이상 프로그래머스의 문제를 풀어야한다
> 다음 Pull Request 작성 규칙을 따른다

깃헙을 사용하는 방식은 사람마다 다르고 다양하지만,
원활한 코드리뷰를 위해 우리 스터디만의 사용 규칙을 정하도록 하겠습니다!

### 1. 공통 저장소를 자신의 계정으로 fork 받는다.
- 저장소 우측 상단의 Fork버튼을 클릭하면 됩니다.

### 2. fork된 저장소 (공통저장소 아님)을 clone 한다.
- 이 때 fork된 저장소는 자신의 계정으로 fork 받은 저장소겠죠?

### 3. 문제풀이 할 브랜치를 주차별로 생성한다.
- 브랜치 명은 본인실명_주차의 형식으로 합니다.
- 예를들어 내 이름이 `슬기`라면, `seulki_week1`라고 하는게 적절하겠어요.
```ex) git branch seulki_week1```

### 4. 새로 생성한 브랜치 최상위 폴더 하위에 아래와 같은 규칙으로 새로운 디렉토리를 만든다.
- 최상위폴더 / 이름 / 문제명
```ex) gsmhs-2020/김슬기/올바른괄호```

### 5. 해당 문제의 디렉토리 안에 아래와 같은 구조로 solution 파일을 생성한다.
- 공통 저장소를 잘 clone 하였다면 최상위 폴더명은 저장소명과 동일하게 갖춰질거에요.
- 최상위폴더/이름/문제명/sloution.확장자
```ex) gsmhs-2020/크리시/야근지수/solution.py```
- 솔루션 파일에 자신의 문제풀이를 작성합니다.
- 파일명은 문제명을 영작하려 들지 말고, 무조건 solution으로 통일해주세요!

### 6. 풀이가 완료된 소스를 해당 브랜치에 commit, push한다.
- 이 때 소스는 자신의 저장소에만 push 된 상태겠죠?
- 업데이트 된 문제만 commit, push 되도록 잘 관리해주세요 :)
### 7. fork한 저장소로 돌아와 [Compare & Pull Request] 버튼을 클릭하여 Pull Request를 생성한다.
- 왼쪽의 base repository가 공통 저장소의 master이고, 오른쪽의 compare대상이 PR을 보낼 브랜치가 맞는지 잘 확인합니다.
- PR 제목은 [n주차] 이름 - 문제명 형식으로 작성합니다.
```ex) [1주차] 크리시 - 완주하지 못한 선수```
- 2문제 이상 풀었을 경우 콤마로 구분하여 문제명을 나열합니다.
```ex) [2주차] 크리시 - 올바른 괄호, 스킬트리```
- 한 문제씩이라도 PR을 보내서 코드리뷰를 잦게 받습니다.
- 해당 주차에 풀어야 할 문제를 다 못풀었다고해서 코드리뷰를 유예하지 않습니다. (그러다 PR늦게날려서 코드리뷰 제대로 못받으면 안되잖아요 ㅠ.ㅠ)
- commit메세지는 PR 목적에 맞는 내용을 작성합니다.

### 8. Creat Pull Request 버튼을 클릭하여 PR을 보내면 끝!
- PR을 잘 보낸것 같으니 다른 문제를 풀어보며 코드리뷰를 기다리면 됩니다.
- 만약 코드리뷰가 원활히 안 이뤄지는 것 같다면 질의응답 채널에 한 번 말씀해주세요!

### 9. 이제 리더가 남겨주는 피드백을 확인하며 본인이 만족할만한 소스가 될 때 까지 같은 방식으로 PR을 보낸다.
- 어떤 문제는 한번의 리뷰로 해결할 수도 있고, 문제는 풀었지만 코드에 개선이 필요한 경우가 있을 수 있어요. 본인이 적절하게 판단하여 코드리뷰의 효과를 극대화합니다!

### 10. 리뷰 후 만족할만한 소스가 되면 PR을 보낸 본인이 직접 머지한다.
- PR된 상태 : 코드리뷰 진행중인 상태
- merge된 상태 - 코드리뷰가 완료된 상태

### 11. 실수로 잘못 머지했을 경우 Revert기능을 이용하여 PR을 보낸다.
- Revert기능은 https://docs.github.com/en/enterprise/2.13/user/articles/reverting-a-pull-request 참고 해주세요!
