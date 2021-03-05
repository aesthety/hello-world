# hello-world

1. github.com 회원가입
2. git설치 (https://git-scm.com)
3. git ssh 키 설치

4. init특정폴더를 초기화하면서 깃정보생성


git에서 주로 사용하는 명령어 활용방법

-----------------------------------------------------------------------------------------

git remote add origin 깃저장소주소현재 폴더를 업로드할 깃저장소위치를 지정
git config --global user.name  "아이디"
git config --global user.email 이메일주소
git status현재 작업폴더의 상태를 확인
git add . 현재 폴더에서 변경된 모든점을 스테이지에올림
git commit -m "messeg"현재 수정한 사항의 특이점을 기록해서 되돌리기 포인트를 지정
git push origin master 해당폴더를 깃저장소로 업로드
git log 현재 깃 로그를 확인가능
git checkout 커밋아이디해당아이디의 커밋시점으로 되돌아가 확인가능
checkout은 확인만 가능하고 해당 체크아웃에서 새로운 커밋생성 불가능해당 체크아웃에서 새로운 커밋을 만들려면 새로운 브랜치를 만들어야함

git brach -v현재 브랜치정보 확인
git branch 브렌치명새로운 브랜치 생성
git checkout 브랜치명해당 브랜치로 이동
-----------------------------------------------------------------------------------------
remote repository 생성 -> 
local repository 에 가져와야 하고 
git clone을 해 오는건데,
branch --> master 
git add 파일명
git status
git commit -m "파일명"
git log
git push origin master
git branch
git branch function 
git checkout function
git log
git status
git add 파일명
git commit -m "function was created"

merge
conflict
