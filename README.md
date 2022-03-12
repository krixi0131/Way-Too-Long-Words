# Way-Too-Long-Words
```python
n=int(input())
for count in range(n):
    a=str(input())
    if len(a)<=10:
        print(a)
    else:
        print(a[0],end='')
        print(len(a)-2,end='')
        print(a[len(a)-1])

```
