# ⛑️XcodeErrorsLogs

- Out of data
- Source Control 메뉴에서 Pull을 실행한다.
branch 목록에서 원하는 branch 선택한다.
Rebase local changes onto upstream changes를 체크하고 Pull을 실행한다

# Swift에서 =, ==, 그리고 ===
1. = 할당연산자
   - =는 변수에 값을 할당하는 데 사용됩니다.
   - 예를 들어
```swift
let x = 5
```

2. == 동등 연산자
- ==는 두 값이 동일한지 비교하는 데 사용됩니다. 즉, 값이 같은지를 확인합니다.
- 예를 들어:
```swift
let a = 5
let b = 5
if a == b {
    // 두 값은 같습니다.
}

```

3. 일치 연산자 === (참조 타입에서 사용):
   - ===는 두 객체가 동일한 객체를 참조하는지 비교하는 데 사용됩니다. 이는 주로 클래스 인스턴스와 같은 참조 타입에서 사용됩니다.
   - 예를 들어
```swift
class MyClass {
    var value: Int
    init(value: Int) {
        self.value = value
    }
}

let obj1 = MyClass(value: 10)
let obj2 = obj1

if obj1 === obj2 {
    // 두 객체는 동일한 객체를 참조합니다.
}
```
여기서 obj1과 obj2는 같은 객체를 참조하고 있기 때문에 ===는 참을 반환합니다.
===는 참조 타입에서만 의미가 있으며 값 타입에서는 사용되지 않습니
