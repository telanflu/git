# git
### how to use git


- 초기화 방법 : Git 처음 사용 방법
<br/><br/>
1. Github 에서 create repository 를 한다. (레포지토리 이름은 프로젝트명)
2. 내 컴퓨터에 있는 프로젝트 폴더 아이콘 위에서 우클릭을 한다.
3.  Git Bash Here 를 클릭한다.
----------------------------------------------- 이제 명령어 쓰기 시작
4. git init //git 쓸거야
5. git branch -M main //master 를 main으로 변경
6. git add . //수정된 코드 내용 catch
<br/>. 의 의미는 all 과 동일하다 //git add . 는 git add -all 과 동일한 의미이다.
7. git commit -m "first commit" //"       "안에 수정된 코드의 설명을 적는다.
8. git remote add origin https://github.com/내닉네임/레포지토리 이름.git
<br/>위 명령어는 GitHub 사이트에서 복사해서 가져온다 //내 컴퓨터 폴더 - Github 사이트 저장소 이어줌
9. git push origin main // origin = GitHub 저장소 별명
                                  main = 내 컴퓨터 폴더 별명
                                ->내 컴퓨터의 수정내용을 GitHub 저장소에 PUSH (올림)

#################################
<br/>*만약 위 과정을 거치다가 아래 같은 ERROR 나면 ?
<br/>error: failed to push some refs to 'https://github.com/내닉네임/레포지토리이름 에러가뜨면
:
우선 폴더가 비어있으면 텍스트 파일이든 뭐든 만들어서 추가한 다음!
- git pull
- git add .
- git commit -m "first commit"
- git push origin main
<br/>

############## 초기화 이후 Git 사용 방법
<br/>
1. 프로젝트 폴더내 파일의 내용을 수정(코드추가/코드삭제)
<br/>-------------------- git 명령어 시작
2. git add .
3. commit -m "수정된 내용 설명"
4. git push origin main

############ 위 과정을 프로그램 폴더내 파일 내용의 수정이 있는 날마다 실행
<br/>-> git 을 사용 함으로써 프로젝트 관리 효율을 높일 수 있게 된다.

