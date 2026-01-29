# todo_app

# repository 만들 때 처음부터 파일이 존재하게 만들면(ex. README.md , license 등)
# Sourcetree 사용 시 고려할 사항
## 1. Clone으로 시작하기(원격지에 있는 파일부터 시작해서 로컬 repository에 프로젝트 시작하면 OK!)
## 2. 이미 로컬pc(repository)에 있는 파일을 연동할 거라면 Sourcetree로 pull부터 시작하면 branch가 두개가 되어 절대 합칠 수 없다.
## 3. 따라서 git bash로 git CLI 환경에서 명령어로 처리해야 한다. 

```bash
# local repository에서
git init

git remote add origin <원격지 주소>

git pull origin main

# git status 로 staging area에 add 되었는지와 commit 되었는지 확인해보기(여러번 해도 무방)
git add -A

git commit -m '<커밋 메세지>'

git push origin main 
```
