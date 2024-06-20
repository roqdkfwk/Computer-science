# Collection Interface

![Untitled](/images/Collection%20Interface/Untitled.png)

- **List**, **Set**, **Queue**에 상속을 하는 실질적인 최상위 컬렉션 타입이다.
- 즉, 업캐스팅으로 다양한 종류의 컬렉션 자료형을 받아 자료를 삽입하거나 삭제, 탐색 기능을 할 수 있다. (다형성)
    
    
    | 메서드 | 설명 |
    | --- | --- |
    | boolean add(Object o)
    boolean addAll(Collection c) | 지정된 객체(o) 또는 Collection(c)의 객체들을 Collection에 추가 |
    | boolean contains(Object o)
    boolean containsAll(Collection c) | 지정된 객체(o) 또는 Collection의 객체들이 Collection에 포함되어 있는지 확인 |
    | boolean remove(Object o)
    boolean removeAll(Collection c) | 지정된 객체 또는 지정된 Collection에 포함된 객체들을 삭제 |
    | boolean retainAll(Collection c) | 지정된 Collection에 포함된 객체만을 남기고 다른 객체들을 Collection에서 삭제.
    사실상 removeAll의 대칭 버전. (교집합 동작)
    이 작업으로 Collection에 변화가 있으면 true, 없으면 false를 반환 |
    | void clear()  | Collection의 모든 객체를 삭제 |
    | boolean equals(Object o) | 동일한 Collection인지 비교 |
    | int hashCode() | Collection의 hash code를 반환 |
    | boolean isEmpty() | Collection이 비어있는지 확인 |
    | Iterator iterator() | Collection의 iterator를 얻어서 반환 (상위 Iterable 인터페이스를 상속) |
    | int size() | Collection에 저장된 객체의 개수를 반환 |
    | Object[] toArray() | Collectionm에 저장된 객체를 객체배열(Object[])로 반환 |
    | Object[] toArray(Object[] a) | 지정된 배열에 Collection의 객체를 저장해서 반환 |
    
    <aside>
    💡 Collection 인터페이스의 메서드를 보면 요소(객체)에 대한 추가, 삭제, 탐색은 다형성 기능으로 사용이 가능하지만, 데이터를 get하는 메서드는 보이지 않는다. 왜냐하면 각 컬렉션 자료형마다 구현하는 자료 구조가 제각각이기 때문에 최상위 타입으로 조회하기 까다롭기 때문이다.
    
    </aside>