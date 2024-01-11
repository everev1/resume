# Git 😀

- 깃의 영역
    1. Working directory
    2. staging Area
    3. Repository

**★★★ add commit push** 순서 중요

*add*    내 컴퓨터 파일을 스테이지에 추가한다

commit    스테이지에 올라간 파일에 쪽지를 적는다

*push*    스테이지에 올라간 쪽지 파일을 저장소에 밀어 넣는다


Working directory / staging Area / Repository

로컬(내컴퓨터) / 스테이지(무대) / 저장소(깃허브)


- add commit push (VS Code)
    - git init
    - (ls -al / ls -a / ls -l)
    - *git status*
    - git add sample.txt
    - *git status*
    - git config --global user.email "you@example.com"
    - git config --global user.name "username"
    - ese 누른후 :wq
    - git commit -m "first commit" 
    - *git status*   // 상태확인 항상 하기
    - git remote add origin https://github.com/everev1/study.git

- PULL vs clone
    - clone: 내용은 있지만 저장소에 아무것도 없을때(레퍼지토리가 아예 없을 때) git 에 올려놓은 내용을 그대로 복제한다.
    - pull: 저장소(집 컴)에 자료가 있지만 내용 업데이트가 안됨. 싸피컴에서 공부하여 업데이트한 내용을 git pull로 땡겨와서 집 컴 문서를 업데이트한다.

- push commit add (VS code)
    - git clone https://github.com/everev1/study
 
상위 폴더 하나에만  git init 하면 됨 하위 폴더에도 하면 꼬인다.

- git remote add origin remote_repo_url
    - origin: 원격 저장소 별칭
    - remote_repo_url: 주소



-나뭇가지
    - git branch [name]
    - git push origin beomsu // 테스트 서버 만듬
    - pull request // merge 
