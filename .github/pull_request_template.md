## 과제 체크포인트

### 기본과제

- React의 hook 이해하기
- 함수형 프로그래밍에 대한 이해
- Component에서 비즈니스 로직을 분리하기
- 비즈니스 로직에서 특정 엔티티만 다루는 계산을 분리하기

- [x] Component에서 사용되는 Data가 아닌 로직들은 hook으로 옮겨졌나요?
- [x] 주어진 hook의 책임에 맞도록 코드가 분리가 되었나요?
- [x] 계산함수는 순수함수로 작성이 되었나요?

### 심화과제

- 뷰데이터와 엔티티데이터의 분리에 대한 이해
- 엔티티 -> 리파지토리 -> 유즈케이스 -> UI 계층에 대한 이해

- [x] Component에서 사용되는 Data가 아닌 로직들은 hook으로 옮겨졌나요?
- [x] 주어진 hook의 책임에 맞도록 코드가 분리가 되었나요?
- [x] 계산함수는 순수함수로 작성이 되었나요?
- [ ] 특정 Entitiy만 다루는 함수는 분리되어 있나요?
- [ ] 특정 Entitiy만 다루는 Component와 UI를 다루는 Component는 분리되어 있나요?
- [x] 데이터 흐름에 맞는 계층구조를 이루고 의존성이 맞게 작성이 되었나요?

## 과제 셀프회고

### 과제에서 좋았던 부분

- 비즈니스 로직들을 순수함수로 분리하며 테스트하기 좋은 코드를 만들 수 있었습니다.
- 액션에서 계산을 빼가면서 각 함수의 책임을 명확히 하고 테스트하기 좋게 분리할 수 있었습니다.
- 커스텀 훅으로 분리시켜 책임을 명확히하고 로직과 UI를 깔끔히 할 수 있었습니다.

### 과제를 하면서 새롭게 알게된 점

- 순수 함수를 사용하면 테스트 코드 작성이 훨씬 용이하고 예측 가능한 결과를 얻을 수 있다는 것을 배웠습니다
- 함수형 프로그래밍의 장점인 불변성과 부수효과 분리의 중요성을 실제로 경험할 수 있었습니다
- 커스텀 훅을 통해 상태 관리 로직을 재사용 가능한 형태로 추상화하는 방법을 익혔습니다
- 단일 책임 원칙에 따라 함수를 분리하면 코드의 가독성과 유지보수성이 크게 향상된다는 것을 체감했습니다

### 과제를 진행하면서 아직 애매하게 잘 모르겠다 하는 점, 혹은 뭔가 잘 안되서 아쉬운 것들

- 엔티티를 다루는 로직들과 UI들을 분리하는데 FSD가 좋겠다는 생각을 하게되었습니다만 시간 관계상 진행하지 못한점이 아쉽습니다
- 순수 함수와 훅의 적절한 책임 분배 기준을 정하는 것이 아직 명확하지 않습니다
- 더 복잡한 비즈니스 로직에서도 이러한 패턴을 잘 적용할 수 있을지 고민이 됩니다

## 리뷰 받고 싶은 내용이나 궁금한 것에 대한 질문

아키텍처 관련 질문

- FSD에 대해서 짧게 학습했으나 명확히 설계가 되질 않아 적용을 못했습니다. 혹시 이번 과제에서 FSD를 적용한 best practice가 있다면 알려주시면 감사하겠습니다.
