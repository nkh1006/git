# git

### git 설치확인

```
git
```  

### git 환경 설정하기
```
git config --global user.name `your name`
git config --global user.email `your email`
```

### git 초기화       
```
mkdir new-project
cd new-project
git init
```

### git 상태확인
```
git status
```

### git 스테이징 하기
```
git add filename

// 전체
git add .
```

### git 커밋하기
```
git commit -m "commit message"

// 커밋 메세지 수정
git commit --amend
```

### git 로그 확인
```
git log
```

### git 변경사항 확인
```
git diff
```

### git 푸쉬하기
```
git push
```

### git 되돌리기
```
git checkout -- filename
```

### git 스테이징 된 파일 돌리기
```
git reset HEAD filename

// 전체
git reset HEAD

// 최신 커밋 되돌리기
git reset HEAD^
```

### git 특정 커밋으로 되돌리기
```
// git log로 특정 커밋값의 해시값을 복사 해둔다.
git log 

git reset --hard commit hash
```

### git 커밋 삭제하지 않고 되돌리기
```
git revert
```