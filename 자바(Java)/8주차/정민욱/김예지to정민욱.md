## 📌 CS 스터디 피드백 (2025-04-02)

### 1. 답변하지 못한 질문 📝

#### ✅ CMS GC의 단점은 무엇인가요? Java에서 G1 GC를 기본값으로 설정하게 된 이유가 무엇일까요? 
CMS GC의 특징과 목표를 잘 설명해주셨습니다.  
다만, 단점에 대한 부분이 보완되면 더 완성도 있는 답변이 될 것 같습니다.

#### ✅ GC가 있어도 메모리 누수가 해결되지 않는 이슈가 발생하는 원인에 대해 설명해주세요.
static 키워드를 통한 예시가 좋았습니다.  
다만, 질문에서 GC와 메모리 누수와 연관지어 "도달할 수 없는 객체의 회수"와 같은 명확한 표현을 먼저 제시해주시면 좋을 것 같습니다.
static도 결국 참조가 남아 있는 객체로 인해 메모리 누수로 이어질 수 있는 거라 이 부분을 강조해주시면 좋을 것 같습니다.

#### ✅ Object 타입의 value를 String으로 타입 캐스팅하는 것과 String.valueOf()를 사용하는 것의 차이점에 대해 설명해주세요.
모든 세부 내용을 알고 있지 않더라도 부분 지식을 활용해 추측하신 점이 좋았습니다.  

다만, 추측하시는 상황에서는 조금 추상화된 답변이 점수를 더 얻어갈 수 있을 것 같습니다.  
"아마 예외가 던져졌을 것 같습니다, 널 체크가 있을 것 같습니다." 형태의 답변은 디테일로 인해 정답률을 낮출 수 있다고 생각합니다.    
추측하는 상황임을 밝히고 "안정적인 처리를 할 것 같습니다"와 추상적인 표현으로 답변하는 것도 좋아보입니다.  

추가로, String.valueOf()의 null 처리를 찾아보시면 좋을 것 같습니다.  

#### ✅ 제네릭 PECS에 대해 설명해주세요.

#### ✅ 인스턴스 메서드와 static 메서드에 synchronized 키워드를 사용했을 때 어떻게 다른가요?
둘은 동기화에 사용되는 락의 대상이 다릅니다.
멀티스레드 환경에서는 이 락의 대상으로 인해 완전히 다른 결과가 나올 수 있어서 보완하시면 좋을 것 같습니다. 

#### ✅ synchronized는 성능적으로 어떠한 영향을 줄 수 있을까요?
synchronized는 busy waiting을 사용하지 않습니다. 
monitor lock과 wait-notify를 학습해보시면 좋겠습니다.  

### 2. 좋았던 점 ✨
- 본인이 알고 있는 지식의 범위 안에서 자신있게 유추하려는 모습이 인상적이었습니다.

### 3. 보완하면 좋을 점 💡
- 명확하지 않은 개념은 조금 추상화해서 표현하는 것도 좋은 전략이라고 생각합니다. ex) 인덱스 아웃오브 인덱스 -> 인덱스가 범위를 벗어나는 경우  
