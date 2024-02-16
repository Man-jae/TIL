# Delegates (위임)

## Delegate Pattern
- 소프트웨어 엔지니어링에서 `delegate pattern (위임 패턴)`은 객체 합성이 상속과 동일하게 코드 재사용을 할 수 있도록 하는 객체 지향 패턴입니다.  
- 위임 패턴은 디자인 패턴중 하나로, 한 객체가 다른 객체로부터 기능 일부를 넘겨받아 데이터를 제공하거나 특정 작업을 수행 할 수 있게 하는 것 입니다.
- 객체 지향에서는 상속을 허용하지 않는 클래스에 새로운 기능을 추가할 때 위임을 사용할 수 있습니다.
- 위음을 사용하면 상속하지 않고 기존 기능을 그대로 사용하면서 새로운 기능을 추가할 수 있습니다.
- Kotlin 에서는 Delegate pattern 을 `by` 라는 키워드로 제공하고 있습니다.
- `by` 키워드는 delegation 을 직접 구현하는 데에서 생기는 보일러 플레이트 코드의 감소를 목적으로 사용됩니다.

</br>

## Delegate 사용의 장점
#### 코드 중복 줄이기
- 기능을 다른 개체에 위임하여 코드 재사용을 방지합니다.
#### 코드 가독성 및 유지 관리성 향상
- 클래스 논리를 더 작은 조각으로 나누어 코드를 더 이해하기 쉽고 유지 관리하기 쉽게 만들 수 있습니다.
#### 코드 재사용 활성화
- 인터페이스 메서드 또는 클래스 가능 구현을 재사용할 수 있으므로 중복 코드를 줄일 수 있습니다.
#### 계층 구조
- 논리가 상속 계층 구조에 묶이지 않도록 개체 계층 구조를 구성할 수 있습니다.