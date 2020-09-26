# 빅콘테스트 nsShop+

### To Do:

- [ ] 24절기 추출:

  공공데이터포털 24절기 데이터를 이용하여 태양황경을 추출

  태양황경의 인덱스와 날씨데이터의 인덱스를 이용하여 merge

  태양황경값을 season 열에 1,2,3,4 (봄, 여름, 가을, 겨울)로 replace 

- [ ] 2019년 이외에도 yTest 데이터와 열값이 일치해야 함으로 evaluation 파일도 계절 열을 추가하기!

- [ ] 진원: 계절, 강수량 빼는이유 상관관계(원우)
- [ ] 찬주: 소비자 심리지수, 주문량
- [ ] 희원: 시청률 
- [ ] 원우: 요일(카테고리화)2020, 휴일, M,D,H
- [ ] evaluation.xlsx 에는 시청률 데이터 컬럼이 없으므로 시청률을 예측해서 넣어주기

데이터 예측 참고:

논문 [시계열 데이터와 랜덤 포레스트를 활용한 시간당 초미세먼지 농도 예측](http://koreascience.or.kr/article/JAKO202013261020958.pdf) 에서 [머신 러닝으로 금 시세를 예측 해보자 feat. ARIMA](https://predictor-ver1.tistory.com/3) 아리마 보다는 랜덤포레스트 사용을 추천

- [ ] 머더코드(mothercode) 및 상품코드 컬럼을 astype('category')
- [ ] 상품군 -> label(숫자로 변환 2020/09/25 수업(인코딩 참조)) -> 원핫인코딩 할것 (getdummies)
- [ ] 





# 파워포인트 (PPT)

- [Adobe 색상 추출](https://color.adobe.com/ko/create/color-wheel)
- 주황색 계열 사용 (nsmall.com)

