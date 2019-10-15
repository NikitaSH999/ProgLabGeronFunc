## Решение Задачи на Питоне

```python
def geron(a, b, c):
    p = (a+b+c)/2
    s = (p*(p-a)*(p-b)*(p-c))**0.5
    return s

q = int(input())
w = int(input())
e = int(input())

a,b,c = [q,w,e]
S = geron(a,b,c)

print ('Площадь =',S, '\n')
```
