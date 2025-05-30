# 빅데이터 프로그래밍 팀 Front 👍
이 프로젝트는 2가지 주제에 대해 데이터를 분석하는 프로젝트 입니다. 
첫 번째는 타이타닉 데이터에 대한 분석이고 두 번째는 공공데이터에 대한 분석입니다. 

## 팀 구성
- **박선우**: 성별에 따른 생존률 분석
- **김동혁**: 티켓 가격 상승에 따른 좌석 및 생존 구분 분석 및 발표
- **박성준**: 도시별 클래스, 요금 가족구성원 분석
- **차성준**: 팀장, 데이터 분석, 문서 취합 및 발표 자료 준비

## 진행 일정
| 일정 | 작업 내용 |
|------|-----------|
| Week 1 | 데이터 수집 및 전처리 |
| Week 2 | 탐색적 데이터 분석 (EDA) |
| Week 3 | 모델링 및 예측 |
| Week 4 | 결과 분석 및 최종 발표 준비 |


## 1: 타이타닉 데이터 분석 

### 분석 개요
타이타닉 호에서의 생존자 데이터를 분석하는 것입니다. 분석을 통해 승객의 생존율을 예측할 수 있는 다양한 인사이트를 도출하고, 생존에 영향을 미치는 주요 요소를 확인할 것입니다.

### 분석 목표
- 타이타닉 승객 데이터를 분석하여 생존율 예측 모델을 구축합니다.
- 다양한 특성(예: 성별, 나이, 클래스 등)이 생존에 미친 영향을 분석합니다.
- 데이터를 시각화하여 통찰을 제공합니다.

### 분석 진행 절차 
1. **데이터 수집**  
   - 사전에 준비한 데이터 사용
     
2. **데이터 전처리**  
   - 결측값 처리
   - 데이터 타입 변환
   - 이상치 처리
     
3. **탐색적 데이터 분석 (EDA)**  
   - 승객의 생존율 분석
   - 다양한 특성이 생존에 미치는 영향 분석
   - 시각화를 통해 데이터 패턴 분석

4. **결과 분석 및 최종 결론**  
   - 분석 결과를 바탕으로 생존율에 영향을 미친 주요 요소 도출
   - 향후 개선사항 및 추가 분석 방향 제시


### 주제 선정 이유
타이타닉 데이터셋은 빅데이터 분석에서 자주 사용되는 문제로, 다양한 데이터 분석 기법을 실습하기에 적합합니다. 또한, 생존율 예측 모델을 만드는 과정에서 실용적인 문제 해결 능력을 기를 수 있습니다. 본 프로젝트는 데이터 분석, 모델링, 시각화, 그리고 문서화 등 여러 기술을 종합적으로 활용하는 좋은 기회입니다.

### 결론
생존률은 성별, 티켓의 등급, 표값, 자녀나 부모 여부 순으로 달라지는 것을 확인할 수 있었다. 

## 2: 범죄 분석

### 분석 개요
지역별, 업종별, 장소별로 범죄를 분석합니다. 분석을 통해 공간적 특성과 범죄의 연관성에 대해서 분석하고 그 상관관계에 대해 표현합니다. 

### 분석 목표
- 공간적 특징이 있는지 조사 
- 데이터를 시각화하여 통찰을 제공

### 분석 진행 절차 
1. **데이터 수집**  
   - 공공데이터 포털:
   - [경찰청_범죄 발생 지역별 통계](https://www.data.go.kr/data/3074462/fileData.do#/layer_data_infomation)
   - [경찰청_범죄 발생 장소별 통계](https://www.data.go.kr/data/3074463/fileData.do#/layer_data_infomation)
     
     
2. **데이터 전처리**  
   - 결측값 처리
   - 데이터 타입 변환
   - 이상치 처리
     
3. **탐색적 데이터 분석 (EDA)**  
   - 전체 범죄건에 대한 분석
   - 장소별 범죄율 분석
   - 지역별 특성과 범죄에 대한 상관 분석
   - 시각화를 통해 데이터 패턴 분석

4. **결과 분석 및 최종 결론**
   - 분석 결과를 바탕으로 범죄와 연관된 주요 공간적 요소 도출


### 주제 선정 이유
지역과 장소와 범죄가 어떤 상관관계가 있는지 분석하여 진상을 밝해내고 사전 범죄 예방에 도움이 되기 위함. 

범죄에 위치적인 특성이 존재한다면 사전에 방지하기 용이할 것으로 생각하여서 주제를 선정하였음. 

### 결론
우선 전체적인 범죄 건수는 꾸준히 감소하는 추세를 띄고 있으며 강력범죄또한 그런 것으로 나타났다.   
범죄 장소 분석에 따라서 가장 강력범죄가 많이 발생하는 장소는 노상, 유흥접객업소, 단독주택, 아파트 였다.   
그리고 전체 범죄에 대해선 2023년 가장 최근 데이터를 가지고 분석한 결과 일반도로, 아파트, 통행로, 단독주택 순으로 범죄가 나타난 것을 확인 가능했다.   
절도와 폭력범죄에 한하여 가장 많은 장소는 금융권이나 사업권이라고 예상하였으나 유동인구가 많고 인구가 많은 지역 위주였다. 
지역으로 넘어가서 분석을 이어갔다.   
서울에 대해서 분석을 했을 때 지능범죄, 기타, 폭력 범죄, 절도 범죄 순으로 많은 건수가 일어났다는 것을 알수 있었고 
가장 건수가 많은 지능 범죄에 대해 더 상세히 분석한 결과 비수도권에 비하여 수도권이 더 높은 비중을 보였으며 서울의 지능범죄만을 확인했을 땐 강남구가 압도적으로 높은 발생건수를 보였다.   
마지막으론 다시 전체적인 범죄율에 대한 분석을 다시 진행하여 연도별로 어떤 범죄가 가장 높은 비중을 차지하였는지를 알아보았다.   
이 결과를 통해 범죄를 예방할 수 있기를 희망한다.   

