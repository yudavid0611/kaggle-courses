# 1. How Models Work
## Introduction to machine learning models
1. fitting or training models
  - A step of capturing patterns from data
  - fit the model할 때 사용하는 데이터가 traingin data

<hr>

# 2. Basic Data Exploration
- 판다스
  1. 전체 칼럼에 대한 기술통계
    - pandas.DataFrame.describe()
  2. 특정 칼럼에 대한 기술 통계
    - pandas.DataFrame.column_name.describe()
  3. 특정 칼럼의 특정 통계 수치
    - 최대값: pandas.DataFrame.column_name.max()
    - 최소값: pandas.DataFrame.column_name.min()
    - 평균: pandas.DataFrame.column_name.mean()