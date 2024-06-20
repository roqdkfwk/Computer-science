# TreeMap Class

![Untitled](/images/TreeMap%20Class/Untitled.png)

- 이진 검색 트리의 형태로 키(key)와 값(value)의 쌍으로 이루어진 데이터를 저장 (TreeSet과 같은 원리)
- TreeMap은 SortedMap 인터페이스를 구현하고 있어 **key값을 기준으로 정렬**되는 특징을 가지고 있다.
- 정렬된 순서로 key : value 쌍을 저장하므로 빠른 검색(특히 범위 검색)이 가능하다.
- 단, 키와 값을 저장하는 동시에 정렬을 행하기 때문에 저장 시간이 다소 걸린다.
- 정렬되는 순서는 숫자 → 알파벳 대문자 → 알파벳 소문자 → 한글 순이다.