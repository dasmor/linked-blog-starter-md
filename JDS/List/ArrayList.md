Implementation of [[List]]. Extends AbstractList

Get complexity O(1)

Add complexity O(1) or O(n) if grow
- При необъявленном размере и первом добавлении создает массив размером Math.max(10, minCapacity)
- При уже объявленом размере или добавленых элементах делает oldCapacity+ Max(minCapacity - oldCapacity, oldCapacity/2)


Remove && indexOf complexity O(n)
