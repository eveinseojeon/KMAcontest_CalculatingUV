## [기상청 날씨 빅데이터 콘테스트 <기상위성 자료를 활용한 여름철 자외선 산출기술 개발>](https://bd.kma.go.kr/contest/main.do)

### ✔ 주제

: 기상위성 자료를 활용한 여름철 자외선 산출기술 개발

### ✔ 데이터

Training data: 2020~2021년(24개월)

Test data: 2022년 6월(1개월)

### ✔ 수행 방법

1. 데이터 전처리
   - knn imputation 기법으로 이상치 처리
   - 변수 변환
   - 파생변수 생성
   - 수치형 변수 정규화
   - 여름철 데이터 추출
2. 분석
   - 다양한 모델 구축하여 성능을 비교해 보고 LSTM 모델 선택
   - 최적의 데이터셋 구성
   - 모델 피팅 

### ✔ 사용 라이브러리

: Os, Pandas, Numpy, Pickle, Tqdm, Sklearn, Matplotlib, Seaborn, Tensorflow, Keras

### ✔ 참여 기간

: 2022.05.23 - 2022.08.03

### ✔ 멤버

: 전인서, [박형준](https://github.com/PHJoon), [형한결](https://github.com/hankaul), [김원빈](https://github.com/BaeJjangE), 노재영

