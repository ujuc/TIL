Date: 2019-01-02 ~
Pre:
Next:

## 2.1 수와 연산

* 사칙 연산 방식

```scheme
(+ 5 5)
(+ -5 5)
(- 5 5)
(* 3 4)
(/ 8 12)
```

* `(연산자 숫자 숫자)`
* Scheme 은 우리가 계산을 하는 방법과 동일한 방법을 사용한다. 가장 안쪽 괄호로 묶인 표현을 계산하여 연산한 값으로 치환, 그 다음 괄호를 연산하는 과정을 반복한다.

### 연습문제

#### 2.1.1

* 제곱에 관련한 연산
    * https://docs.racket-lang.org/htdp-langs/beginner.html?q=square#%28def._htdp-beginner._%28%28lib._lang%2Fhtdp-beginner..rkt%29._sqr%29%29
* sin 값 검색
    * https://docs.racket-lang.org/htdp-langs/beginner.html?q=square#%28def._htdp-beginner._%28%28lib._lang%2Fhtdp-beginner..rkt%29._sin%29%29
* 두 수 중에 큰 수를 결정하는 연산 (Max)
    * https://docs.racket-lang.org/htdp-langs/beginner.html?q=square#%28def._htdp-beginner._%28%28lib._lang%2Fhtdp-beginner..rkt%29._max%29%29

#### 2.1.2

* (sqrt 4) = `2`
* (sqrt 2) = `1.4142135623730951`
* (sqrt -1) = `0+1i`

* tan 값을 계샨하는 연산
    * https://docs.racket-lang.org/htdp-langs/beginner.html?q=square#%28def._htdp-beginner._%28%28lib._lang%2Fhtdp-beginner..rkt%29._tan%29%29
