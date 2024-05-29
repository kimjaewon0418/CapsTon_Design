## CapsTon_Design_Prodect : invigorate the traditional market

---
#### 1. 프로젝트 명
다양한 정보를 담은 앱과 웹을 통한 전통시장 활성화

---
#### 2. 프로젝트 멤버 및 역할
* 김재원(20195135) : 데이터 분석, 수집, 처리와 Firebase Realtime Database 및 Storage 관리
* 류태원(20195135) : 카카오맵 Api를 이용한 지도 생성
* 최종현(20216854) : Swift를 이용한 앱 개발
* 김세희(20171209) : React를 이용한 웹페이지 개발
* 최수진(20213640) : Django를 이용한 로그인 기능 구현

---
#### 3. 프로젝트 목적
조사에 따르면 현존하는 전통시장 진행되는 지역 축제, 각각 지역의 특산물에 대한 정보력이 현저히 떨어지고 있다. 2023년까지 빅데이터 통계를 봤을 때 전통시장에 방문하는 방문자 수, 연 기대 판매 수익은 점점 떨어지고 연기준 흑자보다 적자의 비율이 점점 증가하는 것을 확인할 수 있다. 유튜브와 같은 매체를 봤을 때 연예인 혹은 유튜버들이 전통시장을 찾아 그 지역에 축제나 특산물에 대해서 먹어보고 체험하는 영상을 많이 볼 수 있다. 이러한 영상을 봤을 때, 전통시장, 지역축제, 지역 특산물에 대한 관심은 많은데 이러한 정보를 한번에 편하게 볼 수 있는 웹 혹은 앱과 같은 서비스가 없다는 아쉬움을 느끼게 됐다. 그래서 이번 캡스톤 디자인 수업을 통해 이러한 아쉬움을 해결해줄 수 있는 웹과 앱을 개발한다면 사용자들에게 다양한 정보를 편리하게 줄 수 있는 좋은 결과물이 나올거 같아서 전통시장 활성화라는 주제로 과제를 진행하게 되었다. \
![1](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/2f50e2e4-30e1-49d4-a4c4-fc32325eaa39)

---
#### 4. 프로젝트 소개 및 개발 내용 소개
* 프로젝트 소개 : 본 과제를 수행하기 위해 관리자가 정보를 새로 작성할 수 있는 기능이 있는 웹페이지와, 사용자가 설치하여 사용할 수 있는 iOS 모바일 애플리케이션을 개발하였다
* 개발 내용 소개 : 
1) 웹페이지 UI는 React로 개발하였고, 관리자 로그인을 위한 서비스는 장고, 웹페이지에 지도를 표기하기 위해서는 카카오맵 API를 사용하였다. 
2) 웹사이트에서 지역별 전통시장, 지역축제, 그리고 해당 지역과 관련된 특산물을 확인할 수 있다. 관리자의 경우 로그인 하여 원하는 정보를 추가할 수 있는 기능도 있다.
3) iOS 앱 같은 경우 Swift 언어를 사용해서 개발하였다. 또한 스마트폰(아이폰)에서 그치지 않고, 큰 화면에서도 사용할 수 있게 태블릿(아이패드)용 앱도 동시에 개발하였다. iOS 앱에서도 웹과 마찬가지로, 지역별 전통시장, 축제 등을 확인할 수 있지만, 항상 지니고 다니는 기기이기 때문에 여러 편의 기능도 추가하였다. 대표적으로는 카메라로 계좌번호를 인식하는 기능과 현재 위치 주변 정보를 알려주는 기능이다. 
4) 앱과 웹에서 사용되는 모든 데이터를 저장할 서버로는 Firebase를 사용하였다. Firebase 서버 안에는 앱과 웹에서 사용되는 전통시장, 지역축제, 특산물 등에 대한 정보가 저장되어있고, 관리자가 로그인하여 작성하는 게시글도 이 서버에 저장된다.

---
#### 5. 프로젝트 개발 결과물 
1) Realtime Database의 구조

![1](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/a72ace5b-6924-492b-977f-6467217c3e3f)
![2](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/35ce16dc-01af-45f3-ba8b-9a4ac77e63b2)
![3](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/a8752bf9-69b3-43d6-a733-2aa05cf773f6)

2) Storage의 구조

![4](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/c17d55dd-20aa-4d57-8129-ec65350dbbee)
![5](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/88b7eb58-ce22-4426-94a6-7c64b3f548ad)

3) 메인 홈페이지

![6](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/abdfcf31-b19f-448b-a345-80fcb6a7126b)

3.1) Firebase와 연동한 시장 데이터 

![7](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/39f8cd18-d2ea-4141-b74b-12c292b10216)
3.2) Firebase와 연동한 축제 데이터 

![8](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/2f06a3f0-f451-4561-8f3e-086d592a4ee7)
3.3) 전통시장의 상세 정보

![9](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/2023b211-28a2-4201-aec4-980a9732cbfd)

4) 데이터와 Map 연동
![10](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/f99426fa-c343-47ca-bd84-aebddd942c70)
![11](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/be8ca78f-7416-40f4-b2c3-ee0ca5307d93)

5) Django \
5.1) \
User - 유저 로그인, 로그아웃, 회원정보 수정, 아이디 찾기, 비밀번호 찾지, 가입 시 Firebase에 저장 \
Post - 로그인 후 게시물 작성, 수정, 삭제, 보기 등, FIrebase에 정보 저장
![12](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/9850d5a3-412f-4e3e-bf10-0d53ed4625e4)

5.2) 관리자가 로그인하여 정보 등록
![13](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/803fcf86-343c-4320-a0ba-aafdd164340a)

6) IOS 앱 \
6.1) 축제 유형 분류, 지역에 따른 전통시장 분류 \
![14](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/51e4dab9-dec1-48a7-85c7-e0c14006d2b3)


6.2) 지역에 따른 전통시장 목록, 시장 이미지, 시장명, 주소 \
![15](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/8eaef2a8-f69f-4668-b39b-2893124c97af)
![16](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/709e0507-5d91-43a0-a503-49c9e2c928f0)


6.3) 지역 축제 유형에 따른 분류, 축제명, 축제 시기 \
![17](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/52a00970-e688-4482-ba04-efa9e1e9ee92)
![18](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/5e20dee2-e979-4351-9b4b-443b0ac11ff9)


6.4) 계좌번호 인식 \
![19](https://github.com/kimjaewon0418/CapsTon_Design/assets/71175335/5c9d9515-ab22-4136-95aa-04e9a7f4c7bd)


---
#### 6. 프로젝트 활용방안 및 기대효과
본 과제에서는 사용자 친화적인 모바일 애플리케이션(iOS)과 효율적인 관리자 웹사이트를 개발하였다. 정보 접근성이 부족하고 홍보 수단이 제한적인 전통시장과 지역 특산물에 대한 소비자의 인식을 개선하고 접근성을 향상시키는 것이 목표다. 전통 시장과 지역 축제에 대한 흩어져 있는 정보를 한 곳에 모아 사용자에게 편리하게 제공하고, 관리자는 정보를 수정할 수 있는 웹페이지를 제공함으로써 지역 경제 활성화에 기여하고자 한다. 본 과제는 iOS 기반 모바일 애플리케이션 개발과 웹 기반 관리자 시스템 개발을 통해 사용자 위치 기반 정보 제공, 전통시장, 특산물, 지역 축제 정보 제공, 사용자 맞춤 정보 제공 (즐겨찾기, 검색 기능 등), 실시간 정보 업데이트, 시장 지도 및 편의 서비스 제공 등을 목표로 한다. 본 과제를 통해 지역 경제가 활성화되고 전통시장의 경쟁력이 강화될 것으로 기대된다.




