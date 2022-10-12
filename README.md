## git init
1. git init
    + 새로운 Git 저장소 생성
<br/>

## git status
1. git status
    + 현재 stage 상태를 확인
<br/>

### 파일의 상태 메세지들 
- Tracked : 관리대상
- Modified : 수정됨
- Unmodified : 수정안됨
- Staged : 커밋 대상
- Untracked : 관리대상 아님
<br/>

## git config
1. git config --global user.name "<u>내 이름</u>"

1. git config --global user.email "<u>내 메일주소</u>"

1. git config --list
    + config 보기
<br/>

## git add
1. git add -A
    + 모든 파일의 변경사항을 추가
<br/>

## git commit
1. git commit -m "<u>내용</u>"
    + 추가된 변경 사항을 이력에 추가

1. git commit --amend -m "overide message"
    + 이전 커밋을 포함하여 새 commit 

1. git commit --amend --no-edit
    + 이전 커밋에 추가
<br/>

## git stash
1. git stash 
    + 작업을 임시로 저장

1. git stash list
    + stash 목록을 확인

1. git stash apply
    + stash 내용 복구

1. git stash pop
    + stash를 pop

1. git stash drop
    + 가장 최근의 stash 제거
<br/>

## git log
1. git log -p(--patch)
    + 커밋의 diff 결과를 보여준다
2. git log --graph
    + 브랜치와 머지 히스토리 정보까지 아스키 그래프로 보여준다.
2. git log --pretty
    + 지정한 형식으로 보여준다. 이 옵션에는 oneline, short, full, fuller, format이 있다. format은 원하는 형식으로 출력하고자 할 때 사용한다.
<br/>

## git diff
1. git diff <브랜치이름><다른 브랜치이름>
<br/> 

## git checkout
1. git checkout -b <u>브랜치 이름</u>
<br/>

## git merge
1. git merge <u>브랜치 이름</u>
    + Fast forward merge로 분기한 브랜치의 커밋 히스토리가 기존 브랜치의 커밋 히스토리를 포함하여 병합
2. git merge --no-ff <u>브랜치 이름</u>
    + No Fast forward merge로 분기한 브랜치의 커밋 히스토리가 기존 브랜치의 커밋 히스토리를 포함하지 않고 하나의 히스토리로 병합
<br/>

## git push
1. git push --all
    + 모든 브랜치를 푸쉬
<br/>

## git pull
1. git pull origin <u>브랜치 이름</u>
<br/>

## git 되돌리기 
1. git revert <u>히스토리ID</u>
    + 원하는 히스토리ID 이후의 히스토리를 남기고 히스토리를 추가하여 되돌림
2. git reset --hard <u>히스토리ID</u>
    + 원하는 히스토리ID 이후의 히스토리를 삭제하고 되돌림
