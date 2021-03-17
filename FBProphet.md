## 시계열 데이터와 일반 데이터가 다른 점
일반 데이터는 raw의 순서가 중요하지 않아 traintestsplit을 랜덤하게 진행   
시계열 데이터는 시간과 그 변화가 중요   
-> auto correlation을 이용    

## FBProphet
페이스북에서 만든 라이브러리.  
python api / r api   
sklearn과 비슷 fit, predict 사용   
시계열 + 값 데이터를 model에 fit해준다    
