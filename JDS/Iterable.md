Parent of Collection and his childrens.
```
public interface Iterable<T>
{
  Iterator<T>    iterator();
  
  Spliterator<T> spliterator();

  void           forEach(Consumer<? super T> action);
}
```

![[Pasted image 20240829034148.png]]