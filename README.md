# 팀개발을 위한 깃, 깃허브 
## 챕터 2

코드 추가하고 싶으면,

```sh
$ git init
$ git remote add origin "내 깃허브 원격저장소 링크"
$ git commit -m "챕터2 리드미 파일 작성~"
$ git push origin main
````


## create a new repository on the command line
echo "# pratice" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ingstats/pratice.git
git push -u origin main

## push an existing repository from the command line
git remote add origin https://github.com/ingstats/pratice.git
git branch -M main
git push -u origin main


