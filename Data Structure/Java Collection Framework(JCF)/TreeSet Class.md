# TreeSet Class

![Untitled](./images/TreeSet%20Class/TreeSet1.png)

- 이진 검색 트리(binary search tree) 자료구조의 형태로 데이터를 저장
- 중복을 허용하지 않고, 순서를 가지지 않는다.
- 대신 데이터를 정렬하여 저장하고 있다는 특징이 있다.
- 정렬, 검색, 범위 검색에 높은 성능을 뽐낸다.
  ![이진 검색 트리에 7, 4, 9, 1, 5의 순서로 값을 저장하는 경우](./images/TreeSet%20Class/TreeSet2.png)
  이진 검색 트리에 7, 4, 9, 1, 5의 순서로 값을 저장하는 경우

| **메소드**                                        | **설명**                                               | **시간복잡도** |
| ------------------------------------------------- | ------------------------------------------------------ | -------------- |
| `boolean add(E e)`                                | 지정된 요소를 세트에 추가한다.                         | `O(log n)`     |
| `void clear()`                                    | 세트의 모든 요소를 제거한다.                           | `O(n)`         |
| `boolean contains(Object o)`                      | 세트에 지정된 요소가 있는지 확인한다.                  | `O(log n)`     |
| `boolean isEmpty()`                               | 세트가 비어있는지 확인한다.                            | `O(1)`         |
| `Iterator<E> iterator()`                          | 세트의 요소에 대한 반복자를 반환한다.                  | `O(1)`         |
| `boolean remove(Object o)`                        | 지정된 요소를 세트에서 제거한다.                       | `O(log n)`     |
| `int size()`                                      | 세트의 요소 수를 반환한다.                             | `O(1)`         |
| `E first()`                                       | 세트의 첫 번째(가장 낮은) 요소를 반환한다.             | `O(log n)`     |
| `E last()`                                        | 세트의 마지막(가장 높은) 요소를 반환한다.              | `O(log n)`     |
| `E lower(E e)`                                    | 주어진 요소보다 작은 가장 큰 요소를 반환한다.          | `O(log n)`     |
| `E higher(E e)`                                   | 주어진 요소보다 큰 가장 작은 요소를 반환한다.          | `O(log n)`     |
| `E floor(E e)`                                    | 주어진 요소보다 작거나 같은 가장 큰 요소를 반환한다.   | `O(log n)`     |
| `E ceiling(E e)`                                  | 주어진 요소보다 크거나 같은 가장 작은 요소를 반환한다. | `O(log n)`     |
| `E pollFirst()`                                   | 첫 번째 요소를 제거하고 반환한다.                      | `O(log n)`     |
| `E pollLast()`                                    | 마지막 요소를 제거하고 반환한다.                       | `O(log n)`     |
| `NavigableSet<E> descendingSet(t)`                | 역순으로 정렬된 세트의 뷰를 반환한다.                  | `O(1)`         |
| `SortedSet<E> subSet(E fromElement, E toElement)` | 지정된 범위의 요소를 포함하는 뷰를 반환한다.           | `O(log n)`     |
| `SortedSet<E> headSet(E toElement)`               | 지정된 요소보다 작은 요소의 뷰를 반환한다.             | `O(log n)`     |
| `SortedSet<E> tailSet(E fromElement)`             | 지정된 요소보다 크거나 같은 요소의 뷰를 반환한다.      | `O(log n)`     |
