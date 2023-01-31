# Python code snippets
## Tip1: Counter
```python
from collections import Counter
colors = ['red', 'blue', 'red', 'green', 'blue', 'blue']
cnt = Counter(colors)
cnt
```
> Counter({'red': 2, 'blue': 3, 'green': 1})
***
## Tip2: Enumerate

```python
for i, flavor in enumerate(flavor_list):
    print(f'{i + 1}: {flavor}')
```
