importance: 5

---

# 메서드"f.defer(ms)"를 함수에 추가하기

모든 함수의 프로토타입에 `ms`밀리초 후에 함수를 실행하는 `defer(ms)`함수를 추가하세요.

함수를 프로토타입에 추가한 이후 아래 코드는 동작해야 합니다.

```js
function f() {
  alert("Hello!");
}

f.defer(1000); // 1초 후 "Hello!" 출력
```

인수들은 기존 함수에 전달되는 것을 알아두세요.