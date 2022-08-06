## **Ch5. 형식 맞추기(Formatting)**

### **생각 공유**

**`@ChanhuiSeok`**

---

**`@jjangsungwon`** 

형식을 맞춘 프로젝트는 보기에도 깔끔하고 추가 기능을 구현하기에도 편리하다. 형식을 고민하지 않아도 되니깐.

**행 길이**
- 함수를 명확하게 분리해서 잘 구현하였다면 파일의 행의 수는 큰 의미가 없다고 생각한다.

**빈 행**
- 빈 행은 새로운 개념을 시작한다는 시각적 단서다.
- 파이참은 함수 사이에 2줄 빈 행을 지키도록 안내한다.

**인스턴스 변수 위치**
- C++에서는 클래스 마지막에, 자바에서는 클래스 맨 처음에 인스턴스 변수를 선언한다.
- 나는 저자와 동일하게 잘 알려진 위치에 인스턴스 변수를 모은다는 사실이 더 중요하다고 생각한다.

**종속 함수**
- 호출하는 함수를 호출되는 함수보다 먼저 배치한다.
- 소스 코드 모듈이 고차원에서 저차원으로 자연스럽게 내려갈 수 있다.

**가로 형식**
- 프로그래머는 명백하게 짧은 행을 선호한다.
- 나는 vscode 에서 코드를 작성할 때 보통 모니터의 절반을 사용한다. 따라서, 행의 길이가 모니터의 절반을 넘어가지 않도록 노력한다.
- 공백을 통해 개념을 분리한다는 설명은 인상깊었음. (ex, 괄호 사이에는 공백을 넣지 않았다. 함수와 인수는 서로 밀접하기 때문)
- 우선순위를 표현하는 공백은 오히려 가독성이 떨어진다고 생각했음. 공백으로 인해서 우선순위가 명확하게 구분된다고 생각하지 않았음.

**들여쓰기**
- python은 4칸, vue는 2칸 팀 규칙으로 정하고 개발하고 있음. vue는 들여쓰기를 사용하는 빈도가 python에 비해서 많기 때문에 4칸으로 할 경우 코드를 보기가 불편함
- 짧은 if, while 문은 한 줄로 작성하는게 더 깔끔하다고 생각했었다. 하지만, 책을 읽은 후 들여쓰기 규칙을 적용하는게 더 깔끔하다고 생각이 바꼈다.

**팀 규칙**
- 프로그래머라면 각자 선호하는 규칙이 있다. 하지만 팀에 속한다면 자신이 선호해야 할 규칙은 바로 팀 규칙이다.
- 팀 규칙을 정한 후 lint, prettier 를 설정하여 개발을 진행하고 있다. 코드 구현 후 저장하면 규칙에 맞지 않는 코드는 알아서 규칙에 맞도록 수정된다.
---

**`@qrlagusdn`** 

---
