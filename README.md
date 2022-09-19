# Statute-Searching



: 법령과 판례를 간단하고 빠르게 검색할 수 있는 서비스입니다.


<br>

### Branch Naming

- `main` : 항상 안정된 빌드이자 사용자에게 서비스 중인 브랜치

- `develop` : 개발 상황 취합 브랜치

- `feature-#0-abcd` : 이슈번호가 0번인 abcd 기능 개발 브랜치 

<br>

### Branch Strategy

```
1. 모든 feature 브랜치는 develop 브랜치에서 클론한다.
2. feature 브랜치는 기능, issue 단위로 구분한다.
3. feature 작업이 끝나면 develop branch로 pull request 한다.
4. pull request에서 코드 리뷰를 진행한다.
5. merge 후 브랜치는 삭제한다.
6. develop branch에서 모든 취합이 끝나면 main으로 pull request 한다.
```

<br>

### Commit Convention

- commit message 예시 : `회원가입 기능 구현`
- description(선택) 예시 : `회원가입 JWT 토큰 발급까지 완성`
