# 모던 자바스크립트 Deep Dive: 자바스크립트의 기본 개념과 동작 원리

- 저자: 이용모
- 출판사: 위키북스

## 목표

- 자바스크립트 기초를 검토하고 탄탄히 다지기 위함
- 어떤 부분을 놓치고 있는지 파악하기 위함

<details>
<summary>들어가며</summary>

### 자바스크립트의 태생적 특징

- 대부분 프로그래밍 언어: 애플리케이션을 개발하기 위한 범용적인 용도로 설계
- 반면 자바스크립트: 웹페이지의 단순한 보조 기능을 처리하기 위한 제한적인 용도를 목적으로 생김
- 하지만 자바스크립트 또한 FE, BE 영역의 프로그래밍 언어로 사용 가능한 범용 어플리케이션 개발 언어로 성장

### 기본 개념과 동작 원리 이해의 중요성

- 프로그래머 역할: 요구사항을 기반으로 문제 해결을 위한 방안 고민 및 코드 구현
  - 구현된 코드를 의도대로 동작하게 하려면, 컴퓨터 내부에서 어떻게 동작하는지 예측 가능해야 함
- 명확한 의사소통: 문맥에 맞는 정확한 용어를 사용 (협업의 기본!)
- 에러 디버깅 용이: 에러 발생 원인을 이해하고 디버깅

### 학습 방법

- 1 ~ 3 사이클을 반복
- 빨리가는 유일한 방법은 제대로 가는 것이다. - 로버트 마틴(클린코드 저자) -

1. 기본 개념과 동작 원리

- 중요 키워드 우선, 그 외에는 일단 기술 부채로 쌓아두고 진행.
- 완벽한 이해보다는 반복 학습

2. 코딩 스킬

- 문제 해결 방안을 문법을 통해 구체화
- 자신의 능력을 조금 넘어서는 도전을 지속적으로 시도하고 연습

3. 프로젝트

- 더욱 깊은 이해와 협업 경험
- 추가 학습 필요한 사항 파악

</details>

## 목차

- ⬜ 1. 프로그래밍
- ⬜ 2. 자바스크립트란?
- ⬜ 3. 자바스크립트 개발 환경과 실행 방법
- ✅ 4. 변수 - 2022.05.29
- ✅ 5. 표현식과 문 - 2022.05.29
- ✅ 6. 데이터 타입 - 2022.05.29
- ✅ 7. 연산자 - 2022.06.02
- ✅ 8. 제어문 - 2022.06.04
- ✅ 9. 타입 변환과 단축 평가 - 2022.06.04
- ✅ 10. 객체 리터럴 - 2022.06.06
- ⬜ 11. 원시 값과 객체의 비교
- ⬜ 12. 함수
- ⬜ 13. 스코프
- ⬜ 14. 전역 변수의 문제점
- ⬜ 15. let, const 키워드와 블록 레벨 스코프
- ⬜ 16. 프로퍼티 어트리뷰트
- ⬜ 17. 생성자 함수에 의한 객체 생성
- ⬜ 18. 함수와 일급 객체
- ⬜ 19. 프로토타입
- ⬜ 20. strict mode
- ⬜ 21. 빌트인 객체
- ⬜ 22. this
- ⬜ 23. 실행 컨텍스트
- ⬜ 24. 클로저
- ⬜ 25. 클래스
- ⬜ 26. ES6 함수의 추가 기능
- ⬜ 27. 배열
- ⬜ 28. Number
- ⬜ 29. Math
- ⬜ 30. Date
- ⬜ 31. RegExp
- ⬜ 32. String
- ⬜ 33. 7번째 데이터 타입 Symbol
- ⬜ 34. 이터러블
- ⬜ 35. 스프레드 문법
- ⬜ 36. 디스트럭처링 할당
- ⬜ 37. Set과 Map
- ⬜ 38. 브라우저의 렌더링 과정
- ⬜ 39. DOM
- ⬜ 40. 이벤트
- ⬜ 41. 타이머
- ⬜ 42. 비동기 프로그래밍
- ⬜ 43. Ajax
- ⬜ 44. REST API
- ⬜ 45. 프로미스
- ⬜ 46. 제너레이터와 async/await
- ⬜ 47. 에러 처리
- ⬜ 48. 모듈
- ⬜ 49. Babel과 Webpack을 이용한 ES6+/ES.NEXT 개발 환경 구축
- ⬜ 50. SPA
