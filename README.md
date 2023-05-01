# github_connect

##  1.🐯 [깃설치] (https://git-scm.com/download/win)


      git을 통해서 github와 연결할 수 있다.
      
-깃에 올려야할 폴더에 가서 Shift+ 우클릭하여 PowerShell창 열기

      git init
      
      
-.git 폴더가 생성됨

-------------------------
## 2. 🐯 깃 설치후 Git bash 열기

![image](https://user-images.githubusercontent.com/129706893/235417899-e8a120b8-3e2d-49ac-85bc-78fa52bf9719.png)


* 유저이름 설정

      git config --global user.name "hyun"

* 유저이메일 설정하기(반드시 github에 가입했던 이메일주소와 동일해야한다)

      git config --global user.email "dlthgus419@naver.com"

* 내 정보 확인하기

      git config --list

##  ⬆️ 위의 연결은 해당 컴퓨터에서 한번만 실행하면 됨

-------------------------

# github에 코드 업로드하기

 * 초기화
   git init
 * 추가할 파일(폴더안의 내용을 모두 올림)
   git add .
 * 히스토리 만들기(-m은 메세지를 의미, ""안에는 히스토리이름을 적음)
   git commit -m "작업시작"

* Github의 repository를 만들고 그 주소와 연결하기
  git remote add origin https://github.com/sxhyxn/css_flex.git
  
* 연결이 잘 되었는지 확인하기(사용안해도 됨)

    git remote -v

* Github에 올리기
    git push origin master
    
    
![image](https://user-images.githubusercontent.com/129706893/235424935-9b1c99c7-ca3a-4c8e-8691-5385210103ee.png)

-------------------------------
