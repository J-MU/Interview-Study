## 📌 CS 스터디 피드백 (2025-02-05)

### 1. 답변하지 못한 질문
#### - GC
- **메이저 GC의 STW비용이 마이너 GC보다 더 큰 이유는 무엇일까요?**
  - 왜 old 영역이 young영역보다 더 큰지 보시면 좋을 것 같습니다.
#### - 자바 8에서 람다 스트림 도입 이유
  - 빅데이터의 등장, 컬렉션 프레임워크 병렬 처리를 연관 지어서 생각해보시면 좋을 것 같습니다.
#### - OOM(Out of Memory)이 발생하는 이유
  - 힙 관련 1개, GC 관련 1개 대표 에러 메시지 2가지(`Java heap space, GC overhead limit exceeded`)를 보시면 좋을 것 같습니다.
#### - 클래스 vs 객체 vs 인스턴스
  - 어떤 역할과 기능을 갖고있는 추상적으로 존재하는 개념이 `객체`
  - 이거를 자바 코드로 나타내기 위해 쓰는 게 `클래스`라는 도구고 
  - 그 클래스를 new()를 붙여서 메모리에 실체화된 거를 `인스턴스`라고 한다.
  - 메모리의 실체화된 클래스를 인스턴스라고 하는 거기 때문에 객체랑 인스턴스랑 같다고 표현하진 않는다.
  - 이거는 제가 구글링했을 때 안 나와서, 멘토님이 알려주신 거 알려드립니다! (출처: 토끼책)
#### - ThreadLocal
  - `threadLocals`, `inheritableThreadLocals` 2가지 변수 추가 공부하시면 좋을 것 같습니다.

### 2. 좋았던 점 ✨
- 면접 태도가 굉장히 좋습니다. (면접관님이라고 칭하는 것, 생각할 때 물어보고 하는 점)
- 아는 게 많으신 게 티가 납니다.

### 3. 보완하면 좋을 점 💡
- 전반적으로 준비해 오시면 좋을 것 같습니다!
- 아는 게 많아 답변이 길어지는 경우가 있어서 두괄식으로 말씀하시면 좋을 것 같습니다.
