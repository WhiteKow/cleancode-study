## **Ch2. 의미 있는 이름(Meaningful Names)**

### **생각 공유**

**`@ChanhuiSeok`**

**`@jjangsungwon`** 

의미 있는 이름을 짓는 것은 쉬운 것 같지만 여전히 어렵다고 생각한다. (모든 개발자가 비슷한 생각을 할 것이라고 생각한다. 이름 짓는 사이트도 있기 때문에) 그래도 책에 나와있는 규칙을 참고하여 코드를 개발하다 보니까 조금씩 이름 짓는 것에 대한 부담이 사라지고 있다. 특히 지키고자 하는 규칙은 다음과 같다.

- 불필요한 용어 제거
- 최대한 명료하게, 여러 가지 의미로 해석되지 않도록! (ex, reg_temp_job -> register_temporary_job, regular_temporary_job)

코드를 작성하는 시간보다 코드를 읽는 시간이 훨씬 길다. 따라서, 의미 있는 이름에 대해서 고민하는 시간이 길어진다고 하더라도 부담을 느낄 필요가 없고 충분히 고민할 가치가 있다고 생각한다. 이런 고민을 반복하다보면 추후에는 나의 코드를 다른 사람들에게 너무 자랑하고 싶을 정도로 이름 짓는 것에 대해서 자신 있는 개발자가 될 것이라고 확신한다 :) 

**`@qrlagusdn`** 

Choosing good names takes time but saves more than it takes.

- 의도를 확실하게 나타내도록 네이밍해야함
- 네임이 코멘트를 필요로한다면 제대로 네이밍 안된것임
    - 하지만 코멘트에 대해서는 견해차이가 있다.
- List가 아닐 경우가 있을 수 있기 때문에 변수 명에 List를 붙일 때는 확실할때만 붙여야 함
- info, data 둘 다 a, an 처럼 의미 없는 구분점임
    - 근데 `local` 과 `global` 을 구분하는데 `the`, `a` 를 쓰는건 괜찮음
- Noise words are redundant
- 변수 명에 `var` 이런것은 noise하며 redundant하다
- Customer, CustomerObject 의 차이가 애매하다? `Object`는 안써도 된다?
- 발음할 수 있는 이름
    - This matters because programming is a social activity.
- 검색할 수 있는 이름
    - prefix 로 `customer` 이런것 붙이면 안됨!
- 자바 같은 경우는 변수 명에 타입을 입력할 필요가 없음
- **Avoid Mental Mapping (기억력을 믿지마라)**
- 명료함이 최고!
- 한개념에 한 단어
    - get, retrieve 애매하게 섞어 쓰면 안됨!
- 변수 명에 기술 개념 사용
    - 타겟 유저가 확실하게 기술직군 개발자이기 때문에 기술 개념(FIFO .. ) 을 쓰는 것이 괜찮다.


---

### **회의록**

- **작성**
  - 담당자가 summary 폴더에 회의록 파일을 올린다.
  - 담당자가 아닌 멤버들은 생각 공유에 자신의 생각을 작성한다.


