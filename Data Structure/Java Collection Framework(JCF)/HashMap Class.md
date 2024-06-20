# HashMap Class

![Untitled](/images/HashMap%20Class/Untitled.png)

- HashTable을 보완한 컬렉션
- 배열과 연결이 결합된 Hashing형태로, 키(key)와 값(value)을 묶어 하나의 데이터로 저장한다.
- 중복을 허용하지 않고 순서를 보장하지 않는다.
- 키와 값으로 null이 허용된다.
- 추가, 삭제, 검색, 접근성이 모두 뛰어나다.
- HashMap은 비동기로 작동하기 때문에 멀티 쓰레드 환경에서는 어울리지 않는다. (대신 ConcurrentHashMap 사용)