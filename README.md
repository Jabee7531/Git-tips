## git config
1. git config --global user.name "<u>내 이름</u>"

1. git config --global user.email "<u>내 메일주소</u>"


## git status


## git commit "<u>내용</u>"


## git log
1. git log -p(--patch)
<br/> 커밋의 diff 결과를 보여준다
2. git log --graph
<br/> 브랜치와 머지 히스토리 정보까지 아스키 그래프로 보여준다.
2. git log --pretty
<br/> 지정한 형식으로 보여준다. 이 옵션에는 oneline, short, full, fuller, format이 있다. format은 원하는 형식으로 출력하고자 할 때 사용한다.


## git checkout
1. git checkout -b <u>브랜치 이름</u>


## git merge
1. git merge <u>브랜치 이름</u>
<br/>Fast forward merge로 분기한 브랜치의 커밋 히스토리가 기존 브랜치의 커밋 히스토리를 포함하여 병합
2. git merge --no-ff <u>브랜치 이름</u>
<br/>No Fast forward merge로 분기한 브랜치의 커밋 히스토리가 기존 브랜치의 커밋 히스토리를 포함하지 않고 하나의 히스토리로 병합


## git push
1. git push --all
    + 모든 브랜치를 푸쉬

## git pull
1. git pull origin <u>브랜치 이름</u>

## git 되돌리기 
1. git revert <u>히스토리ID</u>
<br/>원하는 히스토리ID 이후의 히스토리를 남기고 히스토리를 추가하여 되돌림
2. git reset --hard <u>히스토리ID</u>
<br/>원하는 히스토리ID 이후의 히스토리를 삭제하고 되돌림
