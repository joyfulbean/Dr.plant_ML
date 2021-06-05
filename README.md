# Plant-Doctor---Machine-Learning
An machine learning model for predicting the sickness of each expensive plants.

#### **2020.1-2020.2**  | **딥러닝을 이용하여 병든 식물 진단기 어플리케이션 개발, 관리자 페이지 개발**

## 시연 영상: https://www.youtube.com/watch?v=v8FeIa-64ao

### ****\[인턴 경험담\]****

저는 미국 캘리포니아PeopleSpace스타트업 프로젝트팀에서2달간 개발을 하였습니다.저에게 요청된 개발 내용은 비싼 식물이 병이 들었을 때,플랜트 닥터 앱을 키고 휴대폰 카메라로 병든 부분을 찍으면 이 식물을 살리는 방법을 알려주는 프로그램을 개발 하는 것 이였습니다.저는 비싼 식물의 병든 사진의 데이터를 얻기가 너무 어려웠고,웹Crawling을 통해 얻은 일반 식물의 병든 사진을 이용해서 트랜스퍼러닝을 한 모델을 만들어 이 문제를 해결 하였습니다.또 저는 안드로이드 스튜디오 앱 개발 경험이 있었기 때문에 사진을 서버에 보내고,서버에서AI모델에서 결과값을 받아 띄워주는 애플리케이션 개발자 역할을 맡았습니다.

### ****\[팀 Logo\]****

![팀logo](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FcHX8Oc%2Fbtq4DivxxDq%2F1m1IbQLMh91GxWASTyBik0%2Fimg.png)

### ****\[설계 및 구현 경험\] ****

****1) 다양한 툴 경험****

![툴](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbWBIHS%2Fbtq4DhwB7BC%2FLR4CUcQps9sNp3HUKSPIfK%2Fimg.png)

****2) 전체 시스템 설계****

![설계](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbWBIHS%2Fbtq4DhwB7BC%2FLR4CUcQps9sNp3HUKSPIfK%2Fimg.png)

앱에서 사용자가 휴대폰 카메라로 병든 식물 찍음 - 서버로 사진 전송 되고, 머신러닝 결과 반환, 데이터 베이스에 저장

![설계2](https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2FbRnCFS%2Fbtq4Di98nUB%2F4VWoYCJfkwt9kSY0NaTUY1%2Fimg.png)

**데이터 베이스에서 추출해서 관리자 페이지에 사용 현황 보여주기**

### ****\[Challenge\]****

******1) 머신러닝 데이터 부족 : 비싼 식물이 병든 사진을 충분히 얻기 어려웠다. ******

******\--> 오버피팅 문제 발생******

**\[해결\] 비싸지 않은 일반 식물들의 병든 데이터로 transfer learning 을 진행하는 방식으로 모델 개선**

