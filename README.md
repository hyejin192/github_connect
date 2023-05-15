# github_connect


## 1. 🎧 [Git설치](https://git-scm.com/download/win)
Git이란, Git을 통해서 github과 연결할 수 있다.
- git에 올려야 할 폴더에 들어간 후 아무것도 선택 안 한 상태로 shift+우클릭 하여 PowerShell 창열기 선택
        
      git init 입력
- .git 폴더 생성 (보이지 않는다면 보기 버튼 선택 => 숨김항목 표시)
- ---------------------
2. 🍰 Git 설치 후 git bash 열기

![image](https://user-images.githubusercontent.com/129017064/235417884-d534f35f-bd68-46fa-9628-250c06c43121.png)
* 📛 유저 이름 설정
        git config --global  user.name "hyejin192" 입력
* 📧 유저 이메일 설정
        git config --global user.email "jini1728@naver.com" 입력
* 내 정보 확인하기
        git config --

### 🩹 위의 연결은 해당 컴퓨터에서 한 번에 실행하면 됨
------------------------------------------

## 🎱 github에 코드 업로드하기
- 초기화

        git init 입력
        
- 추가할 파일(폴더 안에 내용을 모두 올림,  .은 모든 파일을 의미)
        
        git add .
        
- 히스토리 만들기(-m 은 메시지를 의미함 , ""안에는 히스토리 이름을 적용)  
        
        git commit -m "first commit"
        
- github에 repository(README.md 선택 X)를 만들고 그 주소의 연결하기
        
        git remote add origin https://github.com/hyejin192/css_flex.git
        
- 연결이 잘 되었는지 확인하기 (필수x)

        git remote -v
        
![image](https://user-images.githubusercontent.com/129017064/235423114-2dcf82d6-157a-4101-b643-38aafb60640b.png)
- github에 올리기

        git push origin master

  
--------------------------------------------------------------
## ✂️ 수정하여 다시 업로드 할 때 
(git init,git add . , git commit -m "내용" 후)
1. 기존의 코드를 다운 받는 행위를 해야한다
 
        git pull origin master 실행
        
2. 다시 push 해야한다

        git push origin master      
        
--------------------------------------------------------------------
# Github 협업하는 방법

# 사원입장 -------------------------------------------------------
1. 소스코드 다운로드 

        git clone 주소
![image](https://github.com/hyejin192/github_connect/assets/129017064/40923847-800e-4571-bd42-5ca1e48c8562)

2. 새폴더 만들기
        
3. 터미널에 주소 치기

        git clone https://github.com/hyejin192/hanacard.git
     
     
![image](https://github.com/hyejin192/github_connect/assets/129017064/74930d02-5327-4df7-86c1-6ec76de96d0c)

4. 브랜치(branch) 만들기 - 수정해서 다시 올리기
        
        git checkout -b 브랜치이름
        git checkout -b hana 
        
        git add .
        
        git commit -m "수정완료"
        
        git origin 
        git origin hana
        
        
![image](https://github.com/hyejin192/github_connect/assets/129017064/71958e83-a7a0-42fa-8ed7-7745f7cb3c99)

![image](https://github.com/hyejin192/github_connect/assets/129017064/3da56d39-c73e-40a6-ab17-eb88d00ee43f)


