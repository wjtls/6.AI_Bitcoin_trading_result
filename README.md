# AI_Bitcoin_trading_result (2022.2.8 수정)

- 인풋 지표: 본인이 만든 지표, 시장 지표<br/>
- 특이사항:  
   1. 생성 된 인풋 지표를 딥러닝으로 재생성후 학습 시킴 <br/>
   2. 슬리피지 방지하기 위해 open 데이터 사용.
   3. 거래량 고려시 전날의 open 데이터 사용
   4. 타임 프레임: 일봉

## Traning set 결과
![image](https://user-images.githubusercontent.com/60399060/152996989-2f2cfda6-b2fd-4e2a-8a39-f34ab641af82.png)
- 위 그래프: AI의 Portfolio value , 아래 그래프: 비트 코인  (데이터: 일봉 1010일)
- 시장 수익률 : 77.4 %
- AI 수익률 : 54239.5 %
 <br/><br/><br/>

## validation set 결과
![image](https://user-images.githubusercontent.com/60399060/152996777-c3b90284-7522-41aa-8f2f-ee940a168450.png)
- 위 그래프: AI의 Portfolio value , 아래 그래프: 비트 코인  (데이터: 일봉 275일)
- 시장 수익률 : 184 %
- AI 수익률 : 1407 %

 <br/><br/><br/>
 
## Test set 결과
![image](https://user-images.githubusercontent.com/60399060/152996869-7cbc3089-a4dd-470c-a7fa-a257b6e486f4.png)
- 위 그래프: AI의 Portfolio value , 아래 그래프: 비트 코인  (데이터: 일봉 136일)
- 시장 수익률 : 2.2 %
- AI 수익률 : 101.1 %
