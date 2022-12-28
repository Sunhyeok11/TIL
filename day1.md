# day1 정리

## markdown

1. Heading : 문서의 제목이나 소제목

2. [문자열](url)을 이용하여 링크 작성 가능

- [구글](https://google.com)
- [네이버](https://naver.com)

## git

### git bash 명령어

- ls : 목록
- mkdir : 디렉토리 생성
- cd : 디렉토리 이동
- .. : 상위 디렉토리
- . : 현재 디렉토리
- touch 파일명 : 새로운 파일을 생성
- rm  파일명 : 파일 삭제
- rm -r 파일명 : 폴더 삭제

### git 관리
terminal 에서 new terminal을 만든 후 git 정리

- git init : git 저장소를 만들어 git으로 관리
- git add : 변경내용을 모아 추가하기 위해 사용
- git commit : staged 상태의 파일들을 커밋을 통해 버전으로 기록
- modified : 파일이 수정된 상태 (add 명령어를 통하여 staging area로)
- staged : 수정한 파일을 곧 커밋할 것이라고 표시한 상태 (commit 명령어로 저장소)
- committed : 커밋 된 상태
- git log : 현재 저장소에 기록된 커밋을 조회
- git status : git 저장소에 있는 파일의 상태를 확인
  - Tracked : 이전부터 버전으로 관리되고 있는 파일
    - Unmodified : git status에 나타나지 않음
    - Modified : Changes not staged for commit
    - Stafed : Changes to be committed
  - Untracked : 버전으로 관리된 적 없는 파일(파일을 새로 만든 경우)



git 주소 등록
- git config --global user.email "cghhld@naver.com"
- git config --global user.name "SunHyeok"



