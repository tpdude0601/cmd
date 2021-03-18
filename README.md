
## 자꾸 까먹는 git 명령어 정리

`git clone http:blahblah.git`

`git clean -nd | sed s/'^Would remove '// | xargs -I{} touch "{}.keep"` 
모든 디렉토리 한 번에 검사해서 비어있는 디렉토리에 .keep 파일 넣기

`touch .keep` 
.keep 파일 만들기

`git commit -m "commit message"`

`git pull`

`git add .`

`git push origin main`
`git push`

`git config --global user.email="내 이메일"`
`git config --global user.name="내 이름"`

`git config --local user.email="내 이메일"`
`git config --local user.name="내 이름"`

`git init`
