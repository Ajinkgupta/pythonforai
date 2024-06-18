## Sets
- A set is an unordered collection 
- Eliminates duplicate entries.
- Empty set ```my_set= set()```
- ```my_set = {1,2,3,4}```

:- 
- add ``` my_set.add(5) ```
- remove /delete 
``` 
my_set.remove(3)    # Raises KeyError if element not found
my_set.discard(3)   # Does nothing if element not found
my_set.pop()        # Removes and returns an arbitrary element
my_set.clear()      # Removes all elements

```

- Length ```len(my_set)```

### set operations
- union ``` seta.union(setb) ``` or ``` seta | setb```

- Intersection ``` seta.intersection(setb)``` or ``` seta & setb ```

- Difference ``` seta.difference(setb)``` or ``` seta - setb```

- Symmeteric difference (unique elements of both sets) ```seta.symmetric_difference(setb)``` or ``` set ^ setb ```



## Advanced List

- creating list in single line 
```[expression for item in iterable if condition]```

eg : sqaures = [x*x for x in range(0,9) if x%2 == 0]

- Slicing list 
```list[start:end:step]```

- Reverse/sort
```sort(), reverse()```

- Nested List {list in list : multidimensional list }

``` [[1,2],[3,4]]```


- List Copy

```list.copy()```
`list.deepcopy()`

- map / filter 
- ```lambda expression```
map( lambda function, list/range)
filter(lamda condition , )