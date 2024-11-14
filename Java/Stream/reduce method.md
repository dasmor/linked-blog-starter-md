method of [[Stream]]
list.parallelStream().reduce((acc,b) -> acc + b).get(); - returns Optional
System.out.println(list.parallelStream().reduce(0,(acc,b) -> acc + b)); Where 0 is initial value of accamulator
