# Github-upload-method-VScode-

---

### 코딩 업로딩하기 전 (완전 처음일 때)

1. git Downloads

2. git bash 실행
  
3. git config --global user.name "이름"   (git bash에서 입력)
  
4. git config --global user.email "깃허브 가입 email"   (git bash에서 입력)

5. git config --list    (제일 하단 부분에 user.name 과 user.email이 제대로 들어갔는지 확인하기)   (git bash에서 입력)

---

### 해당 파일을 처음 코딩 업로딩 할 때

1. github Repository 만들기

2. VScode에서 터미널 열기

3. 초기화 <br>
    git init

4. 추가할 파일 더하기  <br>
    git add .  <br>
    ex) git add index.html

5. 업로드 될 파일 상태 확인  <br>
    git status

6. 히스토리 만들기   ex) 제목 : "first commit"  <br>
   git commit -m "first commit"
   
7. 프로젝트 파일과 github 계정 연결하기 <br>
   ex) git remote add origin https://github.com/ghvhdh333/aaaaa.git <br>
   이거랑 비슷한 곳 복사해서 붙여넣기

8. 내 계정과 연결됐는지 확인  <br>
   git remote -v

9. github에 업로드하기  <br>
   git push origin master

---

### 업데이트 하는 법

1. 추가할 파일 더하기  <br>
   git add .

2. 히스토리 만들기  <br>
   git commit -m "first commit"

3. github로 올리기  <br>
   git push origin master
   
---

### 팀프로젝트 하는 법

1. github에서 소스코드 다운로드 <br>
   git clone 주소 폴더이름 <br>
   (주소는 깃허브에서 들고와야 함 / 폴더이름은 선택사항이다. (즉 없어도됨) <br> 
   폴더이름을 줄 경우에는 그 폴더가 새로 생성이 되면서 그 안에 코드들이 다운로드가 되고, <br> 
   폴더이름을 안줄 경우에는 깃허브 프로젝트 이름으로 폴더가 자동으로 생기고 그 안에 코드들이 다운로드 된다.)

2. github에서 내 branch(브렌치) 만들기 <br>
   git checkout -b 브렌치이름

3. 내 브렌치에서 소스코드 업데이트하기 <br>
   git add .                        <br>
   git commit -m "first commit"     <br>
   git push origin 브렌치이름        

4. 마스터 브렌치에 소스가져오기       <br>
   git pull origin master           <br>
   pull하기 전에 기존에 소스코드들을 commit을 먼저 해놔야 한다.

5. 브렌치끼리 이동하는 법             <br>
   git checkout 브렌치이름
