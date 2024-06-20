# Queue Interface

![Untitled](/images/Queue%20Interface/Untitled.png)

- 선입선출 FIFO(First-In-First-Out) 구조
- 자바에서는 **Queue**는 인터페이스이고 필요에 따라 큐 컬렉션을 골라 사용할 수 있다.
    
    
    | 메서드 | 설명 |
    | --- | --- |
    | boolean add(Object o) | 지정된 객체를 Queue에 추가
    저장공간 부족 시 IllegalStateException 발생 |
    | Object remove() | Queue에서 객체를 꺼내 반환
    비어있을 경우 NoSuchElementException 발생 |
    | Object element() | 삭제없이 요소를 읽어온다.
    비어있을 경우 NoSuchElementException 발생 |
    | boolean offer(Object o) | Queue에 객체를 저장 |
    | Object poll() | Queue에서 객체를 꺼내서 반환
    비어있을 경우 null을 반환 |
    | Object peek() | 삭제없이 요소를 읽어온다.
    비어있을 경우 null을 반환 |
    
    [PriorityQueue Class](PriorityQueue%20Class%20c7abec97a78e4bffb3cfd814a01cf3db.md) 
    
    [ArrayDeque Class](ArrayDeque%20Class%20aea8029e3e74410485c8404e87d9151a.md) 
    
    [Deque - LinkedList Class](Deque%20-%20LinkedList%20Class%2037c0a8b020dd4ca696082d276b433379.md)