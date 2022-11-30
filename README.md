# Git Blog 만들기!!

## 1. 사용할 테마 고르기 

- [다음](https://jekyllthemes.io/free)과 같은 사이트에서 Lanyon 테마를 고른 뒤 Lanyon 테마의 레포지토리를 fork한다. 이 때 레포지토리 이름을 KOSSseonghyeok.github.io로 설정한다. 

## 2. 로컬과 연동하기 

- ```git clone```
명령어를 이용해 로컬에 복사한다.

## 3. jekyll 설치하기

- ```jekyll new . --force```
명령어를 이용해 해당 디렉토리에 jekyll을 설치한다.

## 4. jekyll 시작해보기

- ```jekyll serve```
명령어를 이용해 jekyll을 시작할 수 있다.

- jekyll을 시작한 뒤 ```http://127.0.0.1:4000/```로 접속하면 된다.

## 5. 테마 파일을 나한테 맞게 수정하기

- _config.yml 파일의 title, email, description 등을 자신과 관련된 정보로 수정한다. 이 때 댓글 기능을 사용할 것이라서 다음과 같은 코드를 추가하였다.

![image](https://user-images.githubusercontent.com/104906731/204805430-ab8f68aa-e098-4284-a855-40aac5aebbd8.png)

- _layouts의 post.html 파일에 댓글 기능을 구현하기 위해 disqus에서 받아온 코드를 추가한다.

![image](https://user-images.githubusercontent.com/104906731/204806170-b669b168-fc59-484a-b5e5-2bcc48caffc6.png)

- 그 외에도 favicon을 수정하거나 사용하지 않을 기능과 파일들(About 버튼, download 버튼, About.md파일 등)을 제거함으로써 테마 파일을 나한테 맞게 수정한다.

## 6. post 만들기

- _posts 디렉토리에 [제목 이름].md 파일을 만든 뒤 자신이 적고 싶은 내용의 post를 마크다운 문법으로 만든다. 이 때 댓글 기능을 구현할 것이라면
post의 기본 설정에 ```comments: true``` 코드를 추가한다.

ex) ![image](https://user-images.githubusercontent.com/104906731/204807839-3cbdb58f-d7e1-44e9-a69b-0ae41b009538.png)

- 다 만든 포스트는 [여기](https://kossseonghyeok.github.io/)를 통해 볼 수 있다.

## 7. Google Analytics 기능 추가하기

- [여기](https://kossseonghyeok.github.io/jekyll/update/2022/11/26/Google-Analytics.html) 포스트에 자세히 설명해두었다.

## 8. favicon 설정하기

- [여기](https://realfavicongenerator.net/)에서 원하는 이미지를 favicon과 관련된 형식으로 전환한 뒤 public 폴더에 압축을 푼 형태로 저장하고
전환할 때 있는 html코드를 _includes/head.html 파일에 추가한다.


