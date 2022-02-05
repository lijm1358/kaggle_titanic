# kaggle_titanic
Titanic dataset from Kaggle(https://www.kaggle.com/c/titanic)

|    |   Score  |
| -- | -------- |
| 1  | 0.77511  |

### 1.    
* preprocessing
  * PassengerId, Name, Ticket, Cabin drop
  * Embarked 값이 없는 row 제거
  * Age 결측치는 각 Pclass 계층 별 Age 중간값으로 채움
  * 수치형 데이터 표준화
  * Sex column ordinal encoding, Embarked column One-Hot encoding
* model
  * SVM(gamma="auto")