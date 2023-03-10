![Title](https://user-images.githubusercontent.com/105336416/182617216-d4156ce3-f572-44d6-a335-5e7fd9183123.png)

## ✨[굿잡 캘린더 바로가기][goodjob-link]

[goodjob-link]: https://goodjobcalendar.com/ '굿잡 캘린더 바로가기!'

기획

* 취준생들이 일정관리에 어려움을 겪고 있고 채용 일정 관리의 니즈가 있다는 사실을 확인

* 취업 준비생들은 채용 일정관리에 도움이 되는 방법으로 개인에게 맞춰진 취업 일정 관리 서비스를 원하고 있습니다.

* 이러한 니즈를 해결하기 위해 굿잡 캘린더는 잡코리아 연동으로 취업준비생의 개인화된 채용 일정 관리 서비스를 제공하기 위해 기획을 하게 되었습니다.


---

## 💡 주요기능


1️⃣ 이메일 인증을 통한 신뢰감있는 로컬 회원가입 !!
- 비밀번호를 분실해도 이메일로 찾을수 있어요!!

2️⃣ 일일이 하나하나 입력해서 회원가입하기 너무 귀찮을 때는?  
- 카카오 로그인으로 간단하고 안전하게 회원가입 할 수 있어요!!


3️⃣ 나에게 맞는 채용공고만 볼수는 없을까?  
-  추천채용에서 카테고리를 선택하면 나에게 맞는 맞춤형 채용 공고가 와르르!!


4️⃣ 새로운 공고도 보고싶은걸? 
-  잡코리아에서 올라오는 채용공고들을 한시간 단위로 업데이트 해줘서 보여드립니닷!!


5️⃣ 채용공고는 많은데 내 마음에 드는거만 볼 수는 없을까?? 
- `캘린더로 스크랩` 버튼을 통해 나만의 달력으로 `get`


6️⃣ 스크랩은 해놓았는데 너무 많이 했네... 아까 그 공고 어디있더라? 
-  검색창에서 내가 스크랩한 공고를 검색해서 찾을수 있어요!!


7️⃣ 채용공고 말고 다른것도 기록하고 싶은데 흠... 면접 일정이라든가?  
- ➕ 버튼을 눌러서 개인 일정을 작성할 수 있습니다!!✒✒


8️⃣ 회사이름, 제목, 날짜, 시간, 간단한 메모까지 필요한 부분 작성 후 
-  스티커, 배경이미지, 컬러피커까지 꾸미는 다꾸 효과도 뿜뿜!!🎇🎇



## 💎 Architecture

![아키텍쳐](https://user-images.githubusercontent.com/105336416/182626463-fd010fef-c8f9-4879-ba3b-f1dd66383850.png)


## 🕹 How to use
```
1. fork & clone
2. npm install
3. create .env
4. create MySQL DB: npx sequelize db:create
5. npm run dev
6. create seeds: npx sequelize db:seed:all
```
## 🛠 기술스택
<!-- <img src="https://img.shields.io/badge/이름-색상코드?style=flat-square&logo=로고명&logoColor=로고색"/> -->




![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/express-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
<br>
![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
<br>
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=black)
![AWS EC2](https://img.shields.io/badge/AWS%20EC2-%23FF9900.svg?style=for-the-badge&logo=amazon-ec2&logoColor=black)
![AWS RDS](https://img.shields.io/badge/AWS%20RDS-%23527FFF.svg?style=for-the-badge&logo=amazon-rds&logoColor=white)
<br>
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7.svg?style=for-the-badge&logo=Sequelize&logoColor=white)
<br>
![Puppeteer](https://img.shields.io/badge/Puppeteer-%2340B5A4.svg?style=for-the-badge&logo=puppeteer&logoColor=white)
![Nodemon](https://img.shields.io/badge/Nodemon-%2376D04B.svg?style=for-the-badge&logo=nodemon&logoColor=white)
![Babel](https://img.shields.io/badge/Babel-%23F9DC3E.svg?style=for-the-badge&logo=babel&logoColor=black)
<br>
![Passport](https://img.shields.io/badge/Passport-34E27A?style=for-the-badge&logo=Passport&logoColor=black)
<img src="https://img.shields.io/badge/JSON Web Tokens-000000?style=for-the-badge&logo=JSON Web Tokens&logoColor=white">
<br>
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=Jest&logoColor=white)
![PM2](https://img.shields.io/badge/PM2-2B037A?style=for-the-badge&logo=pm2&logoColor=white)
<br>
![Github Actions](https://img.shields.io/badge/Github%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)




## 📌 Feature
1. `Node.js & Express`를 이용한 웹 애플리케이션 서버
2. 유저, 일정, 추천채용공고, 추천채용조건 등 테이블간의 관계를 기반으로 `MySQL` 선택, `Sequelize ORM` 사용
3. `MySQL Profiles`로 쿼리 성능 테스트 및 쿼리 성능 개선 => 데이터 처리 속도 개선
4. `JWT`를 이용한 로그인 인증, 카카오 소셜로그인
5. `puppeteer`를 활용한 크롤러 구현
6. `crontab`을 이용해 매 시 정각 크롤러 자동 실행 => 채용공고 업데이트
7. Github actions, AWS EC2를 활용한 `CI/CD 파이프라인`
8. `AWS RDS`를 이용하여 데이터베이스 분리
9. 모든 API, validator, util에 `jest`를 활용한 유닛 테스트 실시

## 🌠 ERD
![ERD](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/96519750-6922-447f-9748-9fd46a4c700c/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220804%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220804T170144Z&X-Amz-Expires=86400&X-Amz-Signature=84f75ab415a30805eabb3b8b6436e85fa2ffbdb68179ae01f479ec7823bfeecb&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject)


## 🤟 Trouble Shooting
1. https://github.com/rtg1014/goodjob_BE/wiki/%ED%8A%B8%EB%9F%AC%EB%B8%94-%EC%8A%88%ED%8C%85-(1)-pagination
2. 


## 🙋‍♂️ Contributors
|name|position|github|
|------|---|---|
|김성현|Node.js|https://github.com/rtg1014|
|황성원|Node.js|https://github.com/Magiof|
</br>

### ✨[FE repo 바로가기][goodjobFE-link]

[goodjobFE-link]: https://github.com/YoujungSon/Good-Job-Calender '굿잡 캘린더 바로가기!'

<br>

## ⏰ 프로젝트 기간

|||
|:------:|---|
|총 기간| 7월 1일 ~ 8월 5일 (5주)|
|배포일| 8월 1일|
|서비스 개선| 8월 1일 ~ 9월 11일|
