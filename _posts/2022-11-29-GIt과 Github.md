---
layout: post
title: "Git과 GitHub"
date: 2022-11-29 05:34:09 +0900
categories: jekyll update
comments: true
---

## Git이란?
- 본인의 코드와 그 수정내역을 기록하고 관리하도록 돕는 버전 관리 프로그램이다. 로컬 저장소를 사용하기 때문에 다른 개발자와 실시간으로 작업을 공유할 수 없다.
![image](https://user-images.githubusercontent.com/104906731/204385974-b1ecb500-632d-4cf8-a312-3702e5db0bb8.png)

## GitHub란?
-  git 저장소를 관리하는 클라우드 기반 호스팅 서비스이다. 다른 사람과 소스코드 공유가 가능하기 때문에 한 프로젝트에 여러 명의 사람이 참여하여 버전 제어 및 공동 작업이 가능하다.
![image](https://user-images.githubusercontent.com/104906731/204386074-0ea4927e-cc61-4e83-8ec2-1133d274fbe3.png)

### Git과 GitHub의 차이점
- Git은 버전 관리 '프로그램'이고 Github는 버전 관리, 소스 코드 공유, 분산 버전 제어 등등이 가능한 원격 저장소이다.

### Git의 기본 용어
- Local Repository: 본인의 컴퓨터에 저장된 로컬버전의 프로젝트 저장소를 의미하며 개인 전용 저장소이다.

- Remote Repository: 내 컴퓨터가 아닌 원격 서버에 저장되는 프로젝트 저장소를 의미하며 여러명과 함께 공유하기 위한 저장소이다.

- branch: 원래 코드와는 상관없이 독립적으로 개발을 진행할 수 있는 장소이다.

### Git의 세 가지 상태
- Committed: 데이터가 로컬 데이터베이스에 안전하게 저장됐다는 것을 의미한다.

- Modified: 수정한 파일을 아직 로컬 데이터베이스에 커밋하지 않은 것을 의미한다.

- Staged: 현재 수정한 파일을 곧 커밋할 것이라고 표시한 상태를 의미한다.

### Git 명령어

![image](https://user-images.githubusercontent.com/104906731/204386509-00cb4466-2c58-4512-879d-a78c12a441e4.png)


- ```git init```
 
 현재 작업중인 디렉토리를 git 저장소로 지정한다.

- ```git status``` 

현재 Git 상태를 확인한다.

- ```git add``` 

Working Directory 폴더에서 작업한 파일이 있을 경우 add를 통해 staging area로 옮길 수 있다.

- ```git commit``` 

git add 명령어로 스테이지에 추가한 파일을 local repository에 저장한다.

- ```git push``` 

Commit한 이력을 remote repository에 저장하며 현재 폴더를 그대로 업로드하는 것이 아니므로 변경사항을 업데이트하기 위해서는 반드시 add,commit으로 버전을 기록해야한다.

-  ```git branch``` 


branch를 생성한다.

- ```git checkout``` 


현재 작업 중인 branch를 전환한다.

