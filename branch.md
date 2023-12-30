# branch

### git 브랜치 확인
```
git branch
```

### git 브랜치 만들기

```
git branch branch-name
```  

### git 브랜치 이동
```
git checkout branch-name
```

### git 브랜치간 차이 확인하기
```
git log branch-name1..branch-name2
```

### git 브랜치 병합하기
```
git merge branch-name
```

### git 커밋하기전에 잠깐 백업 stash
```
git stash

// stash한 목록 가져오기
git stash pop

// stash한 목록 삭제
git stash drop

// stash한 예전 목록 가져오기
git stash apply
```