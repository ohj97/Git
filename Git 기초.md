# GIT 기초

Clone
```
cd 프로젝트 내려받을 경로
git clone 복사한 URL
cd 폴더명
```

현재 Git을 보내는 경로 확인
```
git remote -v
```

기존의 Git 저장소와 연결 끊기
```
git remote remove origin
```

본인의 Git 저장소로 연결
```
git remote add origin 본인의 Git 프로젝트 URL
```

브랜치 생성 및 이동
```
git branch 생성할 브랜치 이름
git checkout 생성한 브랜치 이름
git branch
```

커밋하기
```
git status
git add .
git commit -m "커밋 메세지"
git push origin 브랜치 이름
```

pull
```
git pull origin 브랜치 이름
```

브랜치 삭제
```
git branch -d 삭제하려는 브랜치 이름
```
