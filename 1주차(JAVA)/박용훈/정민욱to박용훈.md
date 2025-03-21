## 📌 CS 스터디 피드백 (2025-02-05)

### 1. 답변하지 못한 질문
#### - 0.01을 100번 더하면 1이 나올까요?
```
public static void main(String[] args) {
        double value = 0;

        for (int i = 0; i < 100; i++) {
            value +=0.01;
        }

        System.out.println(value);
    }
```
위 코드를 실제로 실행시켜보시면 1.0000000000000007이 나옵니다.
- 소수를 2진수로 표현하는 방법에 대해서 공부해보세요. 10진수에서는 유한소수더라도 2진수에서는 무한소수가 될 수 있습니다.
- float, double의 정밀도 개념에 대해서 공부해보세요.

#### - BigInteger는 어떻게 정수 범위를 벗어나는 값을 저장할 수 있을까?
- 간단히 설명드리자면 int배열을 이용합니다. 내부 코드 한번 살펴 보시면 좋을거같습니다.

#### - HashMap의 특성
  - HashMap의 loadfactor, resize 메서드에 대해서 찾아보시면 좋을 거 같습니다.
  - HashMap의 treeify threshold 에 대해서 찾아보시면 좋을 거 같습니다.
  - hash collision에 대해서 알아보시고 자바의 HashMap은 어떤 걸 채택하여 사용하는지에 대해 공부해보시면 좋을 거 같습니다.
  - hashCode의 결과 값이 같을 때 두 객체는 서로 다른 객체일 수도 있습니다. 컴퓨터 공학에서 통과할 때 100%참은 아니지만 100% 거짓을 빠르게 걸러냄으로써 성능을 향상시킨 사례들이 많습니다. 대표적으로 Bloom Filter같은 것도 공부해보시면 좋을거 같네요.

#### - String
  - String Constant Pool이 무엇인지 그리고 왜 이런게 만들어졌을지에 대해서 고민해보시면 좋을 거 같습니다.
  - 불변객체에 대해서 공부해보시고 StringBuffer/StringBuilder를 사용해야 하는 이유에 대해서 고민해보시면 좋을 거 같습니다.

### 2. 좋았던 점 ✨
- 모르시는 거에 대해서 모른다고 정확히 말씀해주시는 것이 좋았습니다.
- 모르는 것이더라도 생각해보려고 노력하시는 모습이 보여서 좋았습니다.
- JVM쪽에 대해서 공부를 많이 하신 것이 느껴졌습니다.

### 3. 보완하면 좋을 점 💡
- 잘 모르셔도 조금 더 자신감 있게 말씀해주시면 좋을 거 같아요.
- 일정 시간 동안 말씀을 못하시고 정적이 여러 번 있었어요. 아마 속으로 생각하시다 보니 그렇게 된 거 같은데 잠시 생각해본다고 말씀해주시면 더 좋을 듯 합니다.