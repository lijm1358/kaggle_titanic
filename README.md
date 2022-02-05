# kaggle_titanic
Titanic dataset from Kaggle(https://www.kaggle.com/c/titanic)

|    | Score_Test  | Score_Train        |
| -- | ----------- | ------------------ |
| 1  | 0.78468     | 0.8211695607763023 |
| 2  | 0.77511     | 0.8346654749744638 |
| 3  | 0.77033     | 0.8166624106230846 |

### 1.    
* preprocessing
  * PassengerId, Name, Ticket, Cabin drop
  * Embarked 값이 없는 row 제거
  * Age 결측치는 각 Pclass 계층 별 Age 중간값으로 채움
  * 수치형 데이터 표준화
  * Sex column ordinal encoding, Embarked column One-Hot encoding
* model
  * SVM(gamma="auto")
### 2.    
* preprocessing
  * PassengerId, Name, Ticket, Cabin drop
  * Embarked 값이 없는 row 제거
  * Age 결측치는 각 Pclass 계층 별 Age 중간값으로 채움
  * 수치형 데이터 표준화
  * Sex column ordinal encoding, Embarked column One-Hot encoding
* model
  * SVM(C=20, degree=2, gamma='auto', kernel='poly')
### 3.    
* preprocessing
  * PassengerId, Name, Ticket, Cabin drop
  * Embarked 값이 없는 row 제거
  * Age 결측치는 각 Pclass 계층 별 Age 중간값으로 채움
  * 수치형 데이터 표준화
  * Sex column ordinal encoding, Embarked column One-Hot encoding
* model
  * RandomForestClassifier(default)