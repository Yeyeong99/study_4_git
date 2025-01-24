# study_4_git

## 세부 사항

### 일정 | 2025.01.31 - 2025.04.09

### Repository 구조

```Markdown
study_4_git
    ㄴ CS
        ㄴ C
            ㄴ [김나연]C.md
            ㄴ [이다혜]C.md
            ㄴ [이유찬]C.md
            ㄴ [이예영]C.md
        ㄴ Arrays
        ㄴ Algorithm
        ㄴ ...

    ㄴ algorithm
        ㄴ 회전하는 문자열
            ㄴ [김나연]1974.py
            ㄴ [이다혜]1974.py
            ㄴ [이유한]1974.py
            ㄴ [이예영]1974.py
```

## 스터디 목적

1. Git 사용법 익히기
2. CS50 강의 훑어보기
3. 알고리즘 풀이 습관화

## CS 스터디 (대면)

[참고자료](https://www.youtube.com/watch?v=cwtpLIWylAw&list=PLhQjrBD2T381WAHyx1pq-sBfykqMBI7V4)

1. 시간: 매주 수요일 점심시간 모임
2. 일주일에 개념 한 개씩

- **모두**: 공부한 자료 md 파일로 각 주제에 맞는 레포지토리에 올리기
  - [이름]CS*개념*이름.md
  - 파일 업로드는 발표 전 일요일 11:59:59까지
- **주제 담당자**: 자신의 파일 기준으로 요약 발표
- **다른 사람들**: 발표 끝 / 중간에 할 수 있는 질문 2개 준비

## 알고리즘 스터디 (비대면)

[참고자료](https://swexpertacademy.com/main/main.do)

1. 일주일에 두 문제씩 풀기를 목표로 함.
2. 풀이 공유 방법
   - 요약: local에서 branch 생성 후 새 branch에서 작업, push, 깃허브 웹 사이트에서 pull-request 수행
     |번호|명령어|설명|
     |:-:|:-:|:-|
     |1|git clone 주소|처음에만 하면 됨
     |2|git branch Yeyeong|Yeyeong이라는 이름의 브랜치 생성. 자신의 이름으로 하면 됨|
     |3|git checkout Yeyeong|Yeyeong이라는 이름의 브랜치로 이동, checkout 대신 switch 써도 됨|
     |4|**git pull origin main**|1) **자신의 브랜치에 있는 상태에서**<br>2) main 브랜치에 업데이트 된 내용(예를 들어 다른 사람들의 pull request로 인해 main이 변했을 경우)를 받아오기 위한 과정<br>3) **안하면 충돌 가능성 높아지니 필수!!**|
     |5| |로컬에서 작업 진행|
     |6|git status|작업 상태 확인|
     |7|git add 파일이름|파일 혹은 . 이용|
     |8|git commit -m "커밋 메세지"|커밋 시 원하는 issue의 넘버를 쓰면 링크가 연동됨. 예를 들어 #2를 쓰면 #2 issue로 연결되는 식|
     |9|git push|레포지토리에 올림|
     |10||git hub 웹사이트에 잘 올라갔는지 확인|
     - 처음에만 1 ~ 10 수행
     - 이후엔 3 ~ 10 수행
        - 현재 자신이 위치한 브랜치 확인하는 방법: git branch 치거나 git bash의 레포지토리 맨 뒤에 괄호 안 이름 확인
        - 만약 git branch 잘못 만들었을 경우: git branch -d 브랜치 이름 하면 됨
3. 한 문제를 똑같이 풀 것

    - pull request 과정에서 다른 사람 코드 리뷰하고 댓글 남기기
