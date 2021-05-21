# 1. 알고리즘 : 효율, 분석, 차수

- 1.1 알고리즘
- 1.2 효율적인 알고리즘 개발의 중요성
  - 1.2.1 순차검색 대 이분검색
  - 1.2.2 피보나치 수열
- 1.3 알고리즘의 분석
  - 1.3.1 시간복잡도 분석
  - 1.3.2 이론의 적용
  - 1.3.3 정확성 분석
- 1.4 차수
  - 1.4.1 차수의 직관적인 소개
  - 1.4.2 차수의 정식 소개
  - 1.4.3 극한을 사용하여 치수를 결정하기
- 1.5 이 책의 개요

## 1.1 알고리즘

- 알고리즘이 시간과 공간의 사용량을 기준으로 얼마나 효율적인지를 분석하는데 관심을 가져야 한다.

- 컴퓨터 프로그래밍은 정렬하기와 같은 특정 작업을 수행하는 개별 모듈을 모아서 구성한다.
- 알고리즘은, 특정 과제(Problem)를 수행하는 모듈의 설계를 중점을 준다.
- 문제에 값이 지정되어 있지 않은 변수를 그 문지의 파라미터(Parameter)라고 한다.
  - 파라미터가 달려있는 문제를 일종의 "문제 패턴"으로 볼 수 있고,
  - 파라미터가 특정 값을 지정하면 "개별 문제"가 된다.
  - 파라미터에 지정할 값을 문제의 입력사례(instance)라고 한다.
- 즉, `특정 입력사례에 대한 해답(Solution)이란` 파라미터를 입력사례로 지정하여 질문한 문제의 해답이다.
- 이러한, 단계별 절차가 바로 알고리즘이고, "문제를 알고리즘으로 푼다(solve)라고 한다."

## 1.2 효율적인 알고리즘 개발의 중요성

알고리즘의 효율성은 언제나 중요하게 고려해야 한다.

### 순차검색 대 이분검색

- 이분검색 : 정렬된 전화번호부의 'ㅎ'이 있을만한 곳을 어림잡아 가서, 너무 뒤로가면 앞으로, 너무 앞으로 가면 뒤로 가는 것을 반복하는 행위
- 순차검색 : ㄱ~z까지 있을만한 것을 모두 순서대로 찾아가는 행위