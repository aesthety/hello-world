# hello-world

1. github.com 회원가입
2. git설치 (https://git-scm.com)
3. git ssh 키 설치

4. init특정폴더를 초기화하면서 깃정보생성


git에서 주로 사용하는 명령어 활용방법

----------------------------------------------------------------------------------------- <br>

git remote add origin 깃저장소주소현재 폴더를 업로드할 깃저장소위치를 지정<br>
git config --global user.name  "아이디"<br>
git config --global user.email 이메일주소<br>
git status현재 작업폴더의 상태를 확인<br>
git add . 현재 폴더에서 변경된 모든점을 스테이지에올림<br>
git commit -m "messeg"현재 수정한 사항의 특이점을 기록해서 되돌리기 포인트를 지정<br>
git push origin master 해당폴더를 깃저장소로 업로드<br>
git log 현재 깃 로그를 확인가능<br>
git checkout 커밋아이디해당아이디의 커밋시점으로 되돌아가 확인가능<br>
checkout은 확인만 가능하고 해당 체크아웃에서 새로운 커밋생성 불가능해당 체크아웃에서 새로운 커밋을 만들려면 새로운 브랜치를 만들어야함<br>

git brach -v현재 브랜치정보 확인<br>
git branch 브렌치명새로운 브랜치 생성<br>
git checkout 브랜치명해당 브랜치로 이동<br>
-----------------------------------------------------------------------------------------<br>
remote repository 생성 -> <br>
local repository 에 가져와야 하고 <br>
git clone을 해 오는건데,<br>
branch --> master <br>
git add 파일명<br>
git status<br>
git commit -m "파일명"<br>
git log<br>
git push origin master<br>
git branch<br>
git branch function <br>
git checkout function<br>
git log<br>
git status<br>
git add 파일명<br>
git commit -m "function was created"<br>

merge<br>
conflict<br>
