# Тип 2 №15787 #
## Задание 1 ##
___
```python
print('w', 'x', 'y', 'z')
for w in range(2):
    for x in range(2):
        for y in range(2):
            for z in range(2):
                if (((x <= y) and (y <= w)) or (z == (x or y))) == False:
                    print(w, x, y, z)
```
**Ответ:** ywzx

# Тип 2 № 27371 #
## Задание 2 ##
___
```python
print("x y z w")
for x in range(2):
    for y in range(2):
        for z in range(2):
            for w in range(2):
                if (((not(x and not(y)) or (not(z) or not(w))) and ((not(w)  or x) or y))) == False:
                    print(x, y, z, w)
```
**Ответ**: yzwx

# Тип 2 №28538 #
## Задание 3 ##
___
```python
print("x y z w")
for x in range(2):
    for y in range(2):
        for z in range(2):
            for w in range(2):
                if (((x and y) <= ((not (z)) or w)) and (((not (w)) <= x) or (not (y)))) == False:
                    print(x, y, z, w)
```
**Ответ**: zwyx

# Тип 8 №18816 #
## Задание 4 ##
___
```python
a = 'РУЧКА'
c = 0
for f in a:
    for g in a:
        for h in a:
            for j in a:
                for k in a:
                    s = f+g+h+j+k
                    if 'К' in s:
                        c += 1
print(c)
```
**Ответ**: 2101
