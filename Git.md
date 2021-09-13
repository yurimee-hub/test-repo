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
git status // 작업내역 확인
git add .