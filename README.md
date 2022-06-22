# Wonbi's Git Study!

## 깃의 기초부터 파헤치기

1. git init
- 깃 추적을 위한 .git 폴더를 생성하는 명령어
- 이 명령을 수행하면 그때부터 깃을 통한 데이터 관리를 할 수 있게 된다.

2. git add, git commit
- 새로운 파일을 만들거나, 기존 파일을 수정한 후 `git add`명령어를 통해 커밋에 추가할 파일들을 선택하고 `git commit`명령어를 통해 커밋을 생성한다.

3. git remote add, git push
- 처음 `git init`을 통해 추적을 시작한 폴더에 GitHub 저장소 주소를 알려준다. 
```
git remote add origin https://github.com/아이디/이름.git
```
- 만들어 둔 커밋들을 푸시하여 깃허브에 업로드한다.
```
git push origin master
```

