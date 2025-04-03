## 📌 CS 스터디 피드백 (2024-03-05)

### 1. 답변하지 못한 질문
#### - 트랜잭션
- 트랜잭션 격리 수준에 대해 InnoDB의 락 관점과 함께 설명해주세요
  - 락 종류인 next key lock, record lock, gap lock에 대해 알아보시면 좋을 것 같습니다.
  - 이상현상은 설명도 물론 좋지만 dirty read, non-repeatable read, phantom read 용어를 사용하면 더 짧게 설명할 수 있을 것 같습니다.
  - 참고자료 1: [MySQL InnoDB Locks](https://dev.mysql.com/doc/refman/8.0/en/innodb-locking.html)
  - 참고자료 2: [Transaction Isolation Levels](https://dev.mysql.com/doc/refman/8.0/en/innodb-transaction-isolation-levels.html)


#### - 조인
- 사실, JOIN은 상당한 시간이 걸릴 수 있기에 내부적으로 다양한 구현 방식을 사용하고 있습니다. 그 예시에 대해 설명해 주세요.
  - [Nested Loop Join](https://dev.mysql.com/doc/refman/8.0/en/nested-loop-joins.html), [Hash Join](https://dev.mysql.com/doc/refman/8.0/en/hash-joins.html), Sort-Merge Join에 대해 알아보시면 좋을 것 같습니다.

- 3중 조인 부터는 동작 방식이 약간 바뀝니다. 어떻게 동작하는지, 그리고 그 방식이 성능에 어떠한 영향을 주는지 설명해 주세요.
  - 조인이 많이 일어날때 급격히 성능이 떨어지는 이유와 어떻게 튜닝을 하면될지 고민해보시면 좋을 것 같습니다. 
  - MySQL의 옵티마이저가 비용기반 접근법을 사용하여 가능 효율적인 조인순서를 선택하는 방식에 대해 알아보시면 좋을 것 같습니다.
  - 성능에 미치는 영향은 조인순서(중간결과 크기), 인덱싱, 알고리즘 선택(중첩루프조인,해시조인) 등이 있습니다. 
  - 참고자료 : [joining-three-tables](https://www.geeksforgeeks.org/joining-three-tables-sql/)

#### - NoSQL
- NoSQL과 RDBMS의 차이점에 대해 설명해주세요.
  - NoSQL의 특징 중 하나인 스키마리스에 대해 설명하시면 좋을 것 같습니다.
  - NoSQL의 장점과 단점을 비교하면서 설명하시면 좋을 것 같습니다.
  - 사례 : MongoDB, Cassandra, HBase, Couchbase 등 간단한 예시를 들어 설명하시면 좋을 것 같습니다.
  - 참고자료 : [NoSQL vs SQL](https://www.integrate.io/blog/the-sql-vs-nosql-difference/)

- 모든 NoSQL 이 키 밸류 해싱 기법을 사용하고 있는 건가요?
  - nosql rdbms 차이점 질문에 nosql이 모두 key-value store인 것과 같이 오해를 하신것 같아, 다시 재차 질문했습니다. 


### 2. 좋았던 점 ✨
- 두괄식 설명으로 빠르게 핵심을 짚어주셔서 좋았습니다. 덕분에 면접관 입장에서 틀린부분과 맞는 부분을 빠르게 파악할 수 있었습니다.
- 트랜잭션의 읽기 일관성에 대한 설명이 명확하고 정확했던 것 같습니다. 좋은 답변들이 꽤 있었습니다. 

### 3. 보완하면 좋을 점 💡
- 면접에서 준비하신 부분을 더 잘 보여줄 수 있게, 애매하거나 모르는 부분은 면접관에게 인지 시켜주는 것이 좋을 것 같습니다.