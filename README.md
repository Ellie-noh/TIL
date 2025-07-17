## Git 에 대한 전반적인 내용 학습 !

로컬 & 원격 저장소

remote



git remote add origin remote_repo_url

로컬 저장소에 원격 저장소 추가



git remote add origin remote_repo_url

origin 추가하는 원격 저장소 별칭

별칭을 사용해 로컬 저장소 한 개에 여러 원격 저장소를 추가 할 수 있음



git remote -v

내가 작업 중인 깃 프로젝트가 어떤 주소의 원격 저장소와 연결되어 있는지 보여줌



git remote add origin remote_repo_url

추가하는 원격 저장소의 URL



push



git push origin master

원격 저장소에 commit 목록을 업로드



git 아 push해줘 origin 이라는 이름의 원격 저장소에 master 이라는 이름의 브랜지를!

git push --set-upstream origin master

맨 첨에 push 할때는 위의 명령어 사용해야 함.



start a.txt

파일 열기



원격 저장소에는 commit 이 올라가는 것

commit 이력이 없다면 push 할 수 없다.



pull&clone

---중요--

git pull origin master

원격 저장소의 변경사항만을 받아옴 (업데이트)

---중요--

git clone remote_repo_url

원격 저장소 전체를 복제 (다운로드)

-> clone 으로 받은 프로젝트는 이미 git init 이 되어 있음



gitignore

Git 에서 특정 파일이나 디렉토리를 추적하지 않도록 설정하는 데 사용되는 텍스트 파일

-> 프로젝트에 따라 공유하지 않아야 하는 것들도 존재하기 때문



주의사항

이미 git의 관리를 받은 이력이 있는 파일이나 디렉토리는 나중에 gitignore 에 작성해도

적용되지 않음

(git rm --cached 명령어를 통해 git 캐시에서 삭제 필요)



ex)

git d.txt

git e.txt

touch .gitignore

gitignore 에 제외할 파일명 적기!

https://www.toptal.com/developers/gitignore

gitignore.io

Create useful .gitignore files for your project

www.toptal.com
해당 사이트에서 추가가능!
