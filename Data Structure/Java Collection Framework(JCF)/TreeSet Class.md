# TreeSet Class

![Untitled](./images/TreeSet%20Class/TreeSet1.png)

- 이진 검색 트리(binary search tree) 자료구조의 형태로 데이터를 저장
- 중복을 허용하지 않고, 순서를 가지지 않는다.
- 대신 데이터를 정렬하여 저장하고 있다는 특징이 있다.
- 정렬, 검색, 범위 검색에 높은 성능을 뽐낸다.
  ![이진 검색 트리에 7, 4, 9, 1, 5의 순서로 값을 저장하는 경우](./images/TreeSet%20Class/TreeSet2.png)
  이진 검색 트리에 7, 4, 9, 1, 5의 순서로 값을 저장하는 경우

| **메소드**                                       | **설명**                                                         | **시간복잡도** |
| ------------------------------------------------ | ---------------------------------------------------------------- | -------------- |
| `V put(K key, V value)`                          | 지정된 키와 값을 맵에 삽입한다.                                  |
| 키가 이미 존재하면 기존 값을 새 값으로 대체한다. | `O(log n)`                                                       |
| `V get(Object key)`                              | 지정된 키에 대응되는 값을 반환한다. 키가 없으면 null을 반환한다. | `O(log n)`     |
| `V remove(Object key)`                           | 지정된 키와 연결된 값을 맵에서 제거한다.                         | `O(log n)`     |
| `boolean containsKey(Object key)`                | 맵에 지정된 키가 있는지 확인한다.                                | `O(n)`         |
| `boolean containsValue(Object value)`            | 맵에 지정된 값이 하나 이상 포함되어 있는지 확인한다.             |                |
| `int size()`                                     | 맵에 포함된 키-값 쌍의 수를 반환한다.                            | `O(1)`         |
| `void clear()`                                   | 맵에 포함된 키-값 쌍의 수를 반환한다.                            | `O(n)`         |
| `K firstKey()`                                   | 맵에서 가장 작은(첫 번째) 키를 반환한다.                         | `O(log n)`     |
| `K lastKey()`                                    | 맵에서 가장 큰(마지막) 키를 반환한다.                            | `O(log n)`     |
| `K floorKey(K key)`                              | 주어진 키보다 작은 키 중 가장 큰 키를 반환한다.                  | `O(log n)`     |
| `K ceilingKey(K key)`                            | 주어진 키보다 크거나 같은 키 중 가장 작은 키를 반환한다.         | `O(log n)`     |
| `K lowerKey(K key)`                              | 주어진 키보다 작은 키 중 가장 큰 키를 반환한다.                  | `O(log n)`     |
| `K higherKey(K key)`                             | 주어진 키보다 큰 키 중 가장 작은 키를 반환한다.                  | `O(log n)`     |
| `Map.Entry<K, V> pollFirstEntry()`               | 맵에서 가장 작은(첫 번째) 키-값 쌍을 제거하고 반환한다.          | `O(log n)`     |
| `Map.Entry<K, V> pollLastEntry()`                | 맵에서 가장 큰(마지막) 키-값 쌍을 제거하고 반환한다.             | `O(log n)`     |
