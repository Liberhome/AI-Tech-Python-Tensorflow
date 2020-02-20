```python
#one requirement
cars=['Tesla','Maserati','Porsche']
for car in cars:
    if car=='Tesla':
        print (car.upper())
    else:
        print (car.title())
```

****
```python
#multiple requirement：
# and
（price_0>1000000）and(price_1<2000000)
# or
（price_0>1000000）or(price_1<2000000)
#in
cars=['Tesla','Maserati','Porsche']
for car in cars:
    if car=='Tesla':
        print (car.upper())
    else:
        print (car.title())
print ('Maserati' in cars)
#not in
print ('Maseratia'not in cars)
```
