git init
git add 이름 
git commit -m 이름
git log
git status
git push origin master
git pull origin master
git log --oneline

원격저장소를 origin으로 사용한다.
git clone <url>
git remote -v 원격저장소 정보확인
git remote add <원격저장소> <url> 원격저장소 추가
git remote rm <원격저장소> 원격저장소 삭제 
git push <원격저장소> <브랜치> 원격저장소에 push
git pull <원격저장소> <브랜치> 원격저장소에 pull

순서 
git init
git add 이름
git add .
git status 
git commit -m '이름'
git log
git remote -v
git remote add 원격저장소 주소
git remote -v
git push origin master

.gitignore  파일을 만들면 git에서 무시
user/  아래에 작성하면 다시 git에서 반응
이미 커밋된것은 어쩔수없다 미리 .gitignore 하자!

초심자용) https://backlog.com/git-tutorial/kr/intro/intro1_1.html
Git 완벽 책) https://git-scm.com/book/ko/v2/%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0-%EB%B2%84%EC%A0%84-%EA%B4%80%EB%A6%AC%EB%9E%80%3F