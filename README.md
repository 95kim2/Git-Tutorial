# Git Commands

###   연결
>##### 클론 사용 (연결 및 다운로드)
>  - git clone [GIT REPOSITORY ADDRESS]
>  - git clone -b [BRANCH NAME] [GIT REPOSITORY ADDRESS]
>##### 곧바로 연결 (연결만)
>  - git init
>  - git remote add [-t master] origin [GIT REPOSITORY ADDRESS]
>##### 연결 확인
>  - git remote -v

###   업로드
>- git add . (또는 git add [FILE NAME])
>- git commit -m "메세지 입력"
>- git push [origin +master]

###   다운로드
>- git pull [origin master]

###   Branch
>#### branch 확인
>  - git branch (-v를 붙이면 +커밋 내역)
>  - git branch [--merged or --no-merged]
>#### branch 생성
>  - git branch [NAME]
>#### branch 삭제
>  - git branch -d [NAME]
>#### branch 수정
>  - git branch -m [BEFORE_NAME] [AFTER_NAME]
>#### branch 연결
>  - git checkout [NAME]
 
