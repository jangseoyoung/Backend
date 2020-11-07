## Primary Key

- 역할 : 테이블에서 특정 row 하나를 식별하는 역할을 함.
  - 특정 컬럼을 Primary Key로 설정하면 Primary Key에 같은 값이 있는 row가 추가되는 것을 DBMS가 자동으로 막아주기 때문에 중복 row가 생길 위험성이 적어짐.
  - 특정 row를 고유하게 나타낼 수 있는 값을 가진 컬럼으로 설정해야 함.
- 종류
  - **Natural Key**
    - 어떤 개체가 갖고 있는 속성을 나타내는 커럼이 Primary Key가 됐을 때 이를 Natural Key라고 함.
    - ex ) 주민등록번호 , 책 ISBN 등
  - **Surrogate Key**
    - 어떤 개체의 실제 속성은 아니지만 Primary Key로 쓰기 위해 추가한 컬럼을 Surrogate Key라고 함.
    - 주로 1부터 순차적으로 증가하는 숫자가 들어가게 됨.
- **Primary Key는 NN(Not Null)이어야 함.**

