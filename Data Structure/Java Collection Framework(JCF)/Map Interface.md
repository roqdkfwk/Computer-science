# Map Interface

![Untitled](Map%20Interface%20884b86960836433584a4eea59b22cbac/Untitled.png)

- **키(Key)**와 **값(Value)**의 쌍으로 연관지어 이루어진 데이터의 집합
- **값(Value)은 중복되어 저장**될 수 있지만, **키(Key)는 해당 Map에서 고유**하다.
- 기존에 저장된 데이터와 중복된 키와 값을 저장하면 기존의 값은 없어지고 마지막에 저장된 값이 남는다.
- 저장 순서가 유지되지 않는다.
    
    
    | 메서드 | 설명 |
    | --- | --- |
    | void clear() | Map의 모든 객체를 삭제 |
    | boolean containsKey(Object key) | 지정된 key 객체와 일치하는 객체가 있는지 확인 |
    | boolean containsValue(Object value) | 지정된 value객체와 일치하는 객체가 있는지 확인 |
    | boolean equals(Object o) | 동일한 Map인지 비교 |
    | Object get(Object key) | 지정한 key객체에 대응하는 value객체를 반환 |
    | int hashCode() | 해시코드를 반환 |
    | boolean isEmpty() | Map이 비어있는지 확인 |
    | Object put(Object key, Object value) | Map에 key객체와 value객체를 연결(mapping)하여 저장 |
    | void putAll(Map t) | 지정된 Map의 모든 key : value쌍을 추가 |
    | Object remove(Object key) | 지정한 key객체와 일치하는 key : value객체를 삭제 |
    | int size() | Map에 저장된 key : value쌍의 개수를 반환 |
    | Set entrySet() | Map에 저장된 key : value 쌍을 Map.Entry 타입의 객체로 저장한 Set을 반환 |
    | Set keySet() | Map에 저장된 모든 key객체를 반환 |
    | Collection values() | Map에 저장된 모든 value객체를 반환 |
    
    <aside>
    💡 Map 인터페이스의 메소드를 보면, key값을 반환할 때, Set 인터페이스 타입으로 반환하고, value값을 반환할 때, Collection 타입으로 반환하는 것을 볼 수 있다.
    Map 인터페이스에서 **키(key)는 중복을 허용하지 않기 때문에 Set 타입으로 반환**하고, 
    **값(value)은 중복을 허용하기 때문에 Collection 타입으로 반환**하는 것이다.
    
    </aside>