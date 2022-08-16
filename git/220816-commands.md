### 커맨드 명령어
- touch 
- ls
- mv
- rm -rf
- mkdir

- cd
- cp

### vim 을 활용한 text edit
- q : 나가기
- i : insert mode
- esc : 모드에서 나가기
- shift + ; on normal mode(esc) : 커멘드모드
- w : 저장!
- wq : 쓰고 나가기
- vim : vim 에디터로 파일을 연다
- cat : 파일 내용 읽기

### VCS(Version Cnontrol System)
- == SCM(Source Code Management)  
< SCM(Software Configuration Management : 형상관리)

### git 시작하기
- git -v : 설치 확인
- git config --global user.name "당신의유저네임"
- git config --global user.email "당신의메일주소"
- git config --global core.editor "vim"
- git config --global core.pager "cat"
- 오입력시 : git config --unset --global core.editor로 수정

### 셋팅
- 깃허브 사이트 내 계성 세팅
- developer settings
- personal access tokens
    - 혹시 모르니 전부체크 후 generate
    - token 카피
- git push origin main
    - user id , token 입력

### 프로젝트 만들기
- git clone 주소
### 파일 만들기
- touch 파일명: 파일 생성
- vi 파일명 : 내용채우기

### file commit
- git status
- git add 파일명
- git status (add 성공여부 확인)
- git commit
- git push

### commit 시 설명 협약
- feat : features 기능 개발 관련
- docs : documentations 문서화 작업
- fix : bug-fix 오류 개선 혹은 버그 패치
- refactor : 개선
- conf : configurations(환경설정, poetry, requirements.txt,...)

- test : test(동작확인 등)
- ci, build, etc..
- ex) 
1. feat: create fizzbuzz.py

    I create this file to practice git.(개요)
2. feat: Add feature that print 'buzz'  
Condition: i is times of 5.




### commit 할 때 기억해야 할 것
- commit은 동작 가능한 최소단위로 자주 할 것.
- 해당 작업단위에 수행된 모든 파일 변화가 해당 commit에 포함되어야 함.
- 모두가 이해할 수 있는 log를 작성할 것.
- Open Source Contribution시 영어가 강제되지만, 그렇지 않을 경우 팀 내 사용 언어를
따라 쓸 것.
- 제목은 축약하여 쓰되(50자 이내), 내용은 문장형으로 작성하여 추가설명 할 것.
- 제목과 내용은 한 줄 띄워 분리할 것.
- 내용은 이 commit의 구성과 의도를 충실히 작성할 것.

### push
- git push origin main


