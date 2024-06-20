# List Interface

![Untitled](List%20Interface%20db924ecd604143c88ade16a34ce872c6/Untitled.png)

- 저장 순서가 유지되는 컬렉션을 구현하는데 사용
- 같은 요소의 중복 저장을 허용
- 배열과 마찬가지로 index로 요소에 접근
- 리스트와 배열의 가장 큰 차이는 리스트는 **자료형 크기가 고정이 아닌 데이터의 양에 따라 동적으로 늘어났다 줄어들 수 있다**는 점이다. (가변성)
- **요소 사이에 빈 공간을 허용하지 않아** 삽입, 삭제를 할 때마다 배열 이동이 일어난다.
    
    
    | 메서드 | 설명 |
    | --- | --- |
    | void add(int index, Object element)
    boolean addAll(int index, Collection c) | 지정된 위치(index)에 객체(element) 또는 컬렉션에 포함된 객체들을 추가 |
    | Object remove(int index) | 지정된 위치(index)에 있는 객체를 삭제하고 삭제된 객체를 반환 |
    | Object get(int index) | 지정된 위치(index)에 있는 객체를 반환 |
    | Object set(int index, Object element) | 지정된 위치(index)에 객체(element)를 저장 |
    | int indexOf(Object o) | 지정된 객체의 위치(index)를 반환(순방향) |
    | int lastIndexOf(Object o) | 지정된 객체의 위치(index)를 반환(역방향) |
    | List subList(int fromIndex, int toIndex) | 지정된 범위(from ~ to)에 있는 객체를 반환 |
    | ListIterator listIterator()
    ListIterator listIterator(int index) | List의 객체에 접근할 수 있는 ListIterator를 반환 |
    | void sort(Comparator c) | 지정된 비교자(comparator)로 List를 정렬 |
    
    [ArrayList Class](ArrayList%20Class%201a947159c6974b47b829d8f7f7621bdf.md) 
    
    [LinkedList Class](LinkedList%20Class%20ae6d5a59adb848a4905bbd0221620020.md) 
    
    [Vector Class](Vector%20Class%20cf1719dd22134c3a9398dcdc78b8e0d4.md) 
    
    [Stack Class](Stack%20Class%206d96294e997748ab94f480ec2c0e6e61.md)