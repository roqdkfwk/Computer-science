# Deque - LinkedList Class

![Untitled](/images/Deque%20-%20LinkedList%20Class/Untitled.png)

- **LinkedList**는 **List 인터페이스**와 **Queue 인터페이스**를 동시에 상속받고 있기 때문에, 스택, 큐 로도 응용이 가능하다.
- 실제로 **LinkedList 클래스**에 큐 동작과 관련된 메서드를 지원한다. (`push`, `pop`, `poll`, `peek`, `offer` … 등)
    
    <aside>
    💡 **큐(Queue)**는 데이터를 꺼낼 때 항상 첫 번째 저장된 데이터를 삭제하므로, **ArrayList**와 같은 배열  기반의 컬렉션 클래스를 사용한다면, **데이터를 꺼낼 때마다 빈 공간을 채우기 위해 데이터의 이동 & 복사가 발생하므로 비효율적**이다. 그래서 큐는 **ArrayList**보다 데이터의 추가, 삭제가 용이한 **LinkedList로 구현하는 것이 적합**하다.
    
    </aside>