# EnumSet Abstract Class

- Enum 클래스와 함께 동작하는 Set 컬렉션이다.
- 중복 되지 않은 상수 그룹을 나타내는데 사용된다.
- 산술 비트 연산을 사용하여 구현되므로 HashSet 보다 훨씬 빠르며, 적은 메모리를 사용한다.
- 단, enum 타입의 요소값만 저장할 수 있고, 모든 요소들은 동일한 enum 객체에 소속되어야 한다.
- EnumSet은 추상 클래스이고 이를 상속한 RegularEnumSet 혹은 JumboEumSet 객체를 사용하게 된다.