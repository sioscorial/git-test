## Git Command

- `git init`
  git init 는 git 저장소를 초기화 하는것을 뜻합니다.

- `git remote add origin <remote repository url>`
  이건 git사이트에 만들어진 저장소와 연결을 시키기 위해 사용해줍니다.

- `git add <file name>`
  git add는 내가 작업한 것을 저장할 때 사용을 해주며, 보통 git add .로 한번에 저장해줍니다.
  git add . 후에는 git status 로 변경상황이 맞는지 확인하며 맞다면 git commit 으로 내용을 적어둡니다.

- `git commit`
  git commit은 game을 예를들어 save point를 뜻합니다.
  git commit -m " 변경사항 " 을 적어서 무엇이 변경되었는지 확인하며 그 상황으로 다시 돌아갈수있는 save poing를 작성합니다.

- `git push origin <branch name>`
  git push는 브랜치이름의 대한 파일들을 git 저장소에 원격으로 올리는것을 말합니다.

- `git pull origin <branch name>`
  git pull은 git 저장소에 있는 내용을 당겨올 때 사용합니다.
  git pull을 할때는 사용하던 branch에서 git add . 와 git commit을 해주고 checkout으로 main으로 이동 후 사용해줍니다.

- `git merge <branch name>`
  git merge 는 병합해주는걸 말합니다.
  git merge를 사용할 때는 git 저장소에 merge된 파일이있을때 아니면 conflict가 되었다면 다른사람이 merge된 파일이 있는 이유이기 때문에
  git pull을 main 에서 해준다음 작업하던 branch로 이동 후 git merge main 을 사용하여 병합해주고
  git merge main을 하게되면 사용하던 js파일에 변경사항이 나오니 그걸 보고 해결해주면됩니다.
