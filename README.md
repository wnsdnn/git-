# git- 사용법
git 파일 가져오기 (clone: 파일 추가)
- git clone (파일 주소)

git 파일 가져오기 (pull: 업데이트?)
- git pull origin(저장소 이름) (branch 이름)

git 올리기 (pull request)
- 1. git add -A  
- 2. git commit -m "메세지 내용"
- 3. git push origin(저장소 이름) (브런치 이름)

git branch
- git branch -r   // branch 확인
- git checkout -b (branch 이름) // branch 만들기

git branch 가져오기
- 1. git remote update
- 2. git remote -r   // 가져올수 있는 branch 확인
- 3. git checkout -t (branch)
 
git remote (저장소)
- git remote -v  // 저장소 확인
- git remote rm (저장소 이름)  // 저장소 삭제
- git remote add (저장소 이름) (주소) // 저장소 만들기 
