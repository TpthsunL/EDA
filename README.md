# EDA

----------01_order_shipping_EDA---------------
### 1. 커머스에서는 시간과 일 양을 본다. 


### 2. 순서

(1) 주문정보와 시각화에 중점
(2) 상풤정보 

### 3. 첨도가 높아도 옆으로 길게 늘어져 있으면 좋고 이쁜 데이터다. 

### 4. 상관관계 비교방법
from scipy import stats
stats.pearsonr(temp_df['order_id']['count'], temp_df['price]['mean']
-> (A,B) A는 상관계수이고, B는 p-value값이다.

### 5. 로지스틱스 분석실 
- 회사마다 하나씩 있다. 
- 가게가 거짓으로 예상시간을 펌핑시킬때 그걸 잡아내서 조정하는 역할을 한다. 
- 주로 업무 : 예상 배송일과 실제 배송일 차이 분석 
- day_diff 그래프에서 음수이면 로지스틱스 분석실에 대상이 된다. 

---------------------------------------------------------------------

----------------분류모델---------------------------

### 6. 로지스틱 회귀분석  
- decision boundary 기준으로 남과 북이냐 처럼 0과 1 중무엇이냐로 나뉨.

### F1, AUC가 가장 많이 쓰인다. 

### 

### 

### 

### 
