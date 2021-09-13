1. Git 설치
2. 사용자 정보 등록    
- 사용자 이름 등록할 때 이름을 잘 기억해야한다
git config --global --list
git config --global user.name '이름'
git config --global user.email '이메일'
git config --global core.autocrlf input
// window 는 git config --global core.autocrlf true

3. 버전 생성
git init
git status // 파일 상태 확인
빨강 이름의 파일을 add 하면 stage 에 올릴 수 있음
git add . // Untracked files 전체
git add 파일명
초록색 글씨로 바뀌면서 버전 생성 준비 완
-> committed~~~
git commit -m '내용
git log // 업로드된 파일 + 메시지 확인

4. 브랜치 생성, 삭제, 이동
master branch -> 핵심
git branch 브랜치명 -> 브랜치 생성
git branch -> 프로젝트에서 관리하고 있는 브랜치
git checkout 브랜치명 -> 해당 브랜치로 이동
git branch -d 브랜치명 -> 브랜치 삭제, 작업 중인 브랜치에서는 X 이동
git checkout -b 브랜치명 -> 브랜치 생성하고 이동

5. 브랜치 병합
git merge 브랜치명 -> 현재 브랜치와 지정한 브랜치가 병합됨
