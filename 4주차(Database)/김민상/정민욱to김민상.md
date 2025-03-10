## 📌 CS 스터디 피드백 (2025-03-05)

### 1. 답변하지 못한 질문 📝

#### ✅ Hash Table의 읽기 시간 복잡도는 O(1)인데, 왜 Index의 자료구조로 Hash Table이 아니라 B-Tree가 주로 사용될까요?
B-Tree의 정렬되어있다는 성질 때문에 얻는 이점이 많습니다.
1. Hash Table 자료구조에서는 범위 탐색이 어렵다는 점. ex) "<",">", ...
2. Hash Table 에서는 LIKE연산이 어렵습니다.
3. Hash Table 에서는 ORDER BY를 어떻게 처리해줘야할까요?

- 참고자료 1: [MySQL 공식문서 B-Tree vs Hash Index](https://dev.mysql.com/doc/refman/8.0/en/index-btree-hash.html)
- 참고자료 2: [B-Tree vs HashMap 비교 블로그](https://bugoverdose.github.io/computer-science/btree-index-and-hash-index/)
- 참고자료 3: [쉬운 코드 youtube: B tree가 왜 Index로 쓰일까?](https://www.youtube.com/watch?v=liPSnc6Wzfk&t=29s)

### 2. 좋았던 점 ✨
- 차분히 본인이 알고 있는 지식을 논리적인 흐름으로 잘 설명해주시는 것이 좋았습니다.
- 본인이 답변할 수 있는 질문과 잘 모르는 영역에 대해서 빠르게 판단을 내리시는 점이 좋았습니다.
- 공부 열심히 하신 티가 납니다. 특히, 상당히 깊이 있게 공부하셨다는 인상을 주셨어요.

### 3. 보완하면 좋을 점 💡
- 첫째, 두괄식 답변. 둘째, 덜어내는 연습이 필요해 보입니다.
  질문에 대한 실제 대답이 나오는 데까지 너무 오래 걸리셨어요. 특히 "Index의 자료구조로 해시 테이블이 아니라 B-Tree가 일반적으로 사용된다고 생각하는지를 범위 탐색과 연관지어 생각해보세요." 라는 질문에서 B-Tree의 특성과 구조에 대해 한참을 설명한 후에야 범위 탐색으로 넘어가셨어요. 면접관 입장에서는 그래서 본론은 언제나오지?라는 생각이 들었습니다. 이게 반복된다면 면접자와 커뮤니케이션이 잘 된다는 인상을 남기기는 힘들어보여요.
  면접관은 B-Tree의 구조에 대해서 이미 알고 계십니다. 프로젝트에서 사용하신 특수 도메인 지식만 아니라면 면접관님은 다 아실거에요. 간단하게만 언급하셔도 되고 꼬리 질문의 여지로 남겨두셔도 괜찮을거같아요. 질문의 길이를 줄이고 두괄식으로 답변하시는 연습을 하시면 좋을거 같습니다.

