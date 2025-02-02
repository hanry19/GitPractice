# 깃허브 협업 연습

 <br />
 
 
> **공부영상**

https://www.youtube.com/watch?v=7uZzmjk_9ds
 

## 1. 계획
 

  1. 정연이가 간단한 test용 파일을 올린다. (db연결 없는 자바 기본 파일) 
  2. 각자 포크해서 브랜치를 만들어본다 
    - 이때 커밋과 클래스 안에 들어갈 내용은 강의에서 나온 것 처럼 의미 없는 것으로 한다 
      (ex :  성준이의 커밋, 오늘은 햇반에 밥을 비벼 먹엇다)
  3. 여러가지 상황에 맞게끔 테스트를 진행한다. 
     - 발생 가능한 상황을 미리 정하여 테스트 진행 


 <br />


## 2. 발생 가능한 상황 정리 
 
 
  <br />


### < 전재 조건 >


팀 저장소에 마스터 파일이 있고, 그걸 기반으로 각자가 작업을 수행한다는 가정 하에 진행


 ### **상황 1.**
  

    내 로컬저장소에서 "부산여행 1" 브랜치 생성 후 [부산여행 가이드.class] 작업 진행. 
    작업이 완료되면 풀리퀘스트 요청
  
   <br />

 ### **상황 2.**
  
    풀리퀘스트 후 a는 [부산여행 가이드.class] 의 내용이 필요하여 pull을 해야하는 상황이다. 
    이때 병합하여 가져오기와 그냥 가져오기 두 두가지를 진행했을 때 차이점을 본다. 
  
   <br />

###  상황 3. 
  
  
     성준이는 [부산여행 가이드.class] 을 마무리하여 풀리퀘스트까지 한 상황이다.
     하지만 중간에 잘못 된 것을 확인하고 수정을 해야한다면 브랜치를 만들어 새로 수정을 할 것인지 
     커밋 되돌리기를 할 것인지 테스트 

 <br />

###  상황 4.
  
  
     상황 3 에서 "부산여행 2" 브랜치를 만들어 [부산여행 가이드.class]을 수정을진행 하였다. 
     풀리퀘스트를 요청 시 충돌이 발생한다면 어떻게 할 수 있는지 테스트 

 <br />

###  상황 5. 
  
 
     성준이는 [부산대 투어 가이드.class]를 "부산의 대학교" 브랜치에 작업을 하고 있다. 
     a 씨는 [바다이야기.class]를 "용궁" 브랜치에서 작업을 하고 있다.
     b 씨는 당장에 [부산대 투어 가이드.class] [바다이야기.class] 의 내용이 필요한 상황이다.
     b씨를 위해 모두가 풀리퀘스트를 요청한 뒤 팀 저장소 마스터와 병합을 하였다. 

    이때, 성준이와 a씨는 어떻게 class수정을 이어가야하는가?
    새로운 브랜치를 만드는 것인지, 해당 브랜치 그대로 사용하는 것인지 



## 3. 발생 가능한 상황 정리 
 
 
  <br />


### < 결과 >


![슬라이드4](https://user-images.githubusercontent.com/63430211/123814518-b7308500-d930-11eb-8900-d3e34240765b.PNG)
![슬라이드5](https://user-images.githubusercontent.com/63430211/123814526-b861b200-d930-11eb-8f86-029553b03322.PNG)
![슬라이드6](https://user-images.githubusercontent.com/63430211/123814530-b992df00-d930-11eb-8137-bf37b9577205.PNG)
![슬라이드7](https://user-images.githubusercontent.com/63430211/123814532-ba2b7580-d930-11eb-9fef-ef28b1e97eaa.PNG)
![슬라이드8](https://user-images.githubusercontent.com/63430211/123814538-bac40c00-d930-11eb-9c88-a67382b6b6df.PNG)



 
