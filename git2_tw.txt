1. git_work2 작업폴더 생성
   - git init  => .git 폴더 

2. .gitignore 세팅 => 버전관리 배제 파일 세팅

3. commit => 구현
  git status  => 생성, 수정, 삭제 => tracking
  git add . => 스테이지에 올리기
  git commit -m  "커밋 메시지"

4. git reset, git revert
  git reset --hard 커밋아이디

5. git branch 생성
  git branch 브랜치명
  git switch 브랜치명
  git branch -d 브랜치명

6. git merge
  git switch main
  git merge add-coach

7. github -> repository 생성
   -> github 인증 세팅
   -> github token 발급
   
   -> 현재 작업 폴더 연결
   git remote add origin https://github.com/dolsam77/ABC.git
   git branch -M main
   git push -u origin main

8. git push, git pull
  git add .
  git commit
  git push  => git patch, git pull =>  충돌 발생 => 조정(판단) git add . , git commit