## 📌 CS 스터디 피드백 (2025-03-12)

### 1. 답변하지 못한 질문 📝

#### - HTTP
- GET,POST,DELETE,PUT 말고도 또 아는 메소드가 있을까요?
  - Trace, HEAD, OPTIONS 등에 대해서도 알아두시면 좋을 것 같습니다.
- 멱등성이 무엇인가요? 그리고 어떤 메소드가 멱등한가요?
  - 실무에서도 멱등키를 통해 해결하는 경우가 있는 만큼, 알아두시면 좋을 것 같습니다.
  - 결제 시스템: Stripe와 Adyen은 결제 요청에서 멱등키를 사용해 중복 충전을 방지합니다.(참고: [stripe api](https://docs.stripe.com/api/idempotent_requests))
- HTTP 상태코드 200 (ok) 와 201 (created) 의 차이에 대해 설명해 주세요.
  - 개발할때 응답으로 자주 반환했던 응답코드라 물어봤습니다.

#### - REST
- API 설계에서 왜 REST를 사용할까요? SOAP를 사용하면 안되나요?
  - REST와 SOAP의 차이점을 물어본 것이었습니다.
  - SOAP이 레거시 시스템에 사용되는 사례가 많아서, REST와 비교하며 설명해주시면 좋을 것 같습니다.



### 2. 좋았던 점 ✨

- 모르는 부분과 아는 부분이 명확히 구분되어 답변해주셔서 이해하기 쉬웠습니다.
- 답변이 뭉개지거나 흘러가는 경우가 없었습니다. 답변이 명확해서 좋았습니다.


### 3. 보완하면 좋을 점 💡

- 가끔 답변이 길어지는 경향이 있었습니다. 간단한 개념 질문에는 간결하게 답변해주시면 좋을 것 같습니다.