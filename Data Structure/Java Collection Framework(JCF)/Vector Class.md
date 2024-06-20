# Vector Class

![Untitled](./images/Vector%20Class/Untitled.png)

- **ArrayList**의 구형 버전(내부 구성이 거의 비슷하다.)
- **ArrayList**와의 차이는 모든 메소드가 동기화(synchronized) 되어있어 Thread-Safe 하다는 점이다.
- 구버전 자바와 호환성을 위해 남겨두었으며 잘 쓰이지는 않는다.
    
    <aside>
    💡 만일 현업에서 컬렉션에 동기화가 필요하면 `Collections.synchronizedList()`메소드를 이용해 ArrayList를 동기화처리하여 사용한다.
    
    </aside>