# Python Conditions and If statements (Kosullu durumlar)

Python matematikteki mantiksal kosullari destekler.

- Equals: `a == b`
- Not Equals: `a != b`
- Less than: `a < b`
- Less than or equal to: `a <= b`
- Greater than: `a > b`
- Greater than or equal to: `a >= b`

Yukaridaki kosullar farkli yerlerde farkli amaclar ile kullanilabilir. Ama en cok `if` ifadesi ile beraber kullaniliyor.

## __`if` :__
bir `if` ifadesi kosul bildirir ve bu sekilde yazilir:
```python
a = 33
b = 200
if b > a:
    print("b is greater than a")
```

## __`elif` :__
`elif`'in Pyhton'daki anlami:

 "eger bir onceki kosul dogru degilse bu kosulu dene" 
```python
a = 33
b = 33
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
```


## __`else` :__
`else` anahtar sözcüğü, önceki koşullar tarafından yakalanmayan her şeyi yakalar.
```python
a = 200
b = 33
if b > a:
  print("b is greater than a")
elif a == b:
  print("a and b are equal")
else:
  print("a is greater than b")
```


```python
a = 200
b = 33
if b > a:
  print("b is greater than a")
else:
  print("b is not greater than a")
```

## __`or` :__

`or` anahtar sözcüğü bir mantıksal işleçtir ve koşullu ifadeleri birleştirmek için kullanılır:

>Test if a is greater than b, OR if a is greater than c:
```python
a = 200
b = 33
c = 500
if a > b or a > c:
  print("At least one of the conditions is True")
```

## __`and` :__

`and` anahtar sözcüğü bir mantıksal işleçtir ve koşullu ifadeleri birleştirmek için kullanılır:

>Test if a is greater than b, AND if c is greater than a::
```python
a = 200
b = 33
c = 500
if a > b and c > a:
    print("Both conditions are True")
```


## __Nested If :__

`if`'in içinde `if` olabilir;
```python
x = 41

if x > 10:
    print("Above ten,")
    if x > 20:
        print("and also above 20!")
    else:
        print("but not above 20.") 
```


    
