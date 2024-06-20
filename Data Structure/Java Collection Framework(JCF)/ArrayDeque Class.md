# ArrayDeque Class

![Untitled](ArrayDeque%20Class%20aea8029e3e74410485c8404e87d9151a/Untitled.png)

- 스택으로 사용할 때 Stack 클래스보다 빠르며, 대기열로 사용할 때는 LinkedList보다 빠르다.
- 사이즈에 제한이 없다.
- null 요소는 저장되지 않는다.
    
    
    | Deque | Queue | Stack |
    | --- | --- | --- |
    | offerLast() | offer() | push() |
    | pollLast() | - | pop() |
    | pollFirst() | poll() | - |
    | peekFirst() | peek() | - |
    | peekLast() | - | peek() |