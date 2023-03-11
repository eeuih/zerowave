# 제로웨이브 (Zerowave)


> ### 프로젝트 소개 
#### 🌱 청년취업사관학교(SeSAC) 용산캠퍼스 웹 풀스택 과정 팀프로젝트로 진행 되었습니다.  

제로웨이브는 친환경에 관심 있는 사용자에게 친환경 정보를 제공하는 웹사이트입니다.    
제로웨이스트샵의 정보와 용기내 챌린지가 가능한 장소의 정보를  카카오맵 API 지도 위에  
리스트와 마커를 통해 알려주며 DB에 저장된 장소의 값을 지도 유형에 따라 불러올 수 있습니다.  
사용자가 장소의 정보를 추가하고 삭제할 수 있도록 CRUD 기능을 구현하고,  
회원 전용 기능을 위해 회원가입, 로그인, 회원 정보 변경, 회원 탈퇴를 구현하였습니다.  

#### 🗓️ 진행 기간 : 2022.12.10 ~ 2022.12.29  

#### 🙌 진행 인원 : 5명 (프론트엔드: 3명, 백엔드: 2명)  

#### 🌏 데모사이트 : http://52.78.48.228:8080/zerowave
→ ID: test@test.com / PW: test12 계정으로 로그인 하실 수 있습니다!  

#### ✔️ 주요 기능  
* 카카오맵 장소 검색    
* 검색한 장소 정보 DB 추가, 삭제    
* 지도 내 장소 즐겨찾기 설정  
* 회원 관련 기능 (회원가입, 로그인, 회원 정보 변경, 탈퇴)  
　  
> ### 사용 기술  
#### 프론트엔드 (FE) 
<div>
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
<img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
</div>  

#### 백엔드 (BE) 
<div>
<img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
<img src="https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=Node.js&logoColor=white">
<img src="https://img.shields.io/badge/express-000000?style=for-the-badge&logo=express&logoColor=white">
</div>  


　  
> ### 담당 구현 기능  
#### 백엔드 (BE) 
1. 지도 페이지 API 구현  
사용자가 지도(Map) 페이지를 사용할 때 클라이언트의 요청이 오면  
서버에서 적절한 응답을 할 수 있도록 API를 작성하였습니다.  
카카오맵의 확대/축소와 크기에 따라 달라지는 위, 경도 값에 따라   
Sequelize op 연산자로 요청된 값 이내의 장소만 선택하여 응답합니다.  
더불어 카카오맵 지도에서 검색한 장소를 DB에 추가하고  
즐겨찾기 기능을 사용할 수 있도록 하였습니다.  

2. DB 설계  
백엔드 팀원 1명과 함께 사용자, 지도를 중심으로 4개의 테이블을 설계하였습니다. 
![image](https://user-images.githubusercontent.com/116782313/224465545-a62fe669-c7a0-410a-88ef-d5baaa8fb8af.png)



### 감사합니다. 😊  




