# Set Interface

![Untitled](./images/Set%20Interface/Untitled.png)

- 데이터의 **중복을 허용하지 않고 순서를 유지하지 않는** 데이터의 집합 리스트
- 순서 자체가 없으므로 인덱스로 객체를 검색해서 가져오는 `get(index)` 메서드도 존재하지 않는다.
- 중복 저장이 불가능하기 때문에 심지어 null값도 하나만 저장할 수 있다.
    
    
    | 메서드 | 설명 |
    | --- | --- |
    | boolean add(E e) | 주어진 객체를 저장 후 성공적이면 true, 중복 객체면 false를 리턴 |
    | boolean contains(Object o) | 주어진 객체(o)가 저장되어있는지 여부를 리턴 |
    | Iterator<E> iterator() | 저장된 객체를 한 번씩 가져오는 반복자를 리턴 |
    | isEmpty() | 컬렉션이 비어있는지 조사 |
    | int Size() | 저장되어 있는 전체 객체의 수를 리턴 |
    | void clear() | 저장된 모든 객체를 삭제 |
    | boolean remove(Object o) | 주어진 객체(o)를 삭제 |