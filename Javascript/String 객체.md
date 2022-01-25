> [바닐라 자바스크립트](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791165921071&orderClick=LEa&Kc=)를 참고하였습니다.

# String 객체
자바스크립트의 내장 객체로, 문자열을 다루기 위한 여러 내장 함수/프로퍼티가 포함되어있다.
## 내장 프로퍼티 VS 내장 함수
* 내장함수엔 ()가 붙는다.
* 코드로 이해하기
```js
let obj = {
    temp1: function() {
        // ...
    },
    temp2: function() {
        // ...
    },
    temp3: 100
};
```
이렇게 내부적으로 temp1, temp2 함수와 temp3 속성값을 갖는 객체가 있다고 할 때,
내장 함수는 `obj.temp1()`, `obj.temp2()` 와 같이 호출되지만
내장 프로퍼티는 `obj.temp3`과 같이 괄호 없이 호출된다!

## String 객체 내장 프로퍼티
- length


## String 객체 내장 함수
- 문자열 자르기
1. substring()
2. substr(): 잘라야 할 문자열의 길이를 알 때.
3. slice(): 마이너스 사용 가능
각 함수의 차이, 쓰임새(각각 어떤 용도인지?) 알기




- 공백 제거
1. trim(): 앞 뒤 공백 없애줌: 데베에 저장하는 값일 떄. 또는 검색일 때.
2. 정규식: 문자열 중간에 포함된 공백을 제거할 때
(다시 공부해야 함)
```js
name.replace(/\s/g, "");
```
