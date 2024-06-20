# Map.Entry Interface

- Map.Entry 인터페이스는 Map 인터페이스 안에 있는 내부 인터페이스이다.
- Map에 저장되는 key : value쌍의 Node 내부 클래스가 이를 구현한다.
- Map 자료구조를 보다 객체 지향적인 설계를 하도록 유도하기 위한 것이다.
    
    ![Map.Entry 내부 인터페이스와 HashMap 안의 Map.Entry를 구현하고 있는 Node 내부 클래스](/images/Map%20Entry%20Interface/Untitled.png)
    
    Map.Entry 내부 인터페이스와 HashMap 안의 Map.Entry를 구현하고 있는 Node 내부 클래스
    
    | 메서드 | 설명 |
    | --- | --- |
    | boolean equals(Object o) | 동일한 Entry인지 비교 |
    | Object getKey() | Entry의 key객체를 반환 |
    | Object getValue() | Entry의 value객체를 반환 |
    | int hashCode() | Entry의 해시코드 반환 |
    | Obejct setValue(Object value) | Entry의 value객체를 지정된 객체로 바꾼다. |

hashmap

linkedhashmap

trreemap

hashtable