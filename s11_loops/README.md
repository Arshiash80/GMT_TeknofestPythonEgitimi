# Python Loops (Donguler)

Python has two primitive loop commands:

1. `while` loops
2. `for` loops


## __The while Loop :__

`while` döngüsü ile bir koşul doğru olduğu sürece bir dizi ifadeyi çalıştırabiliriz.

    Print i as long as i is less than 6:
```python
i = 1
while i < 6:
  print(i)
  i += 1
```

### The `break` Statement
`break` ile `while` koşulu doğru olsa bile döngüyü durdurabiliriz:

    Exit the loop when i is 3:
```python
i = 1
while i < 6:
  print(i)
  if i == 3:
    break
  i += 1 
```

### The `continue` Statement
`continue` ile mevcut donguyu durdurabilir ve bir sonraki ile devam edebiliriz:

    Continue to the next iteration if i is 3:
``` python
i = 0
while i < 6:
  i += 1
  if i == 3:
    continue
  print(i)
```


### The `else` Statement
`else` ifadesi, koşul artık doğru olmadığında calistirilicak kod blogunu belirler,

    Print a message once the condition is false:
```python
i = 1
while i < 6:
  print(i)
  i += 1
else:
  print("i is no longer less than 6")
```

### Sonsuz dongu (infinite loop)
`while` dongusunun kosulu dogru oldugu surece calisiyorsa 

`while True:` ifadesi bizi sonsuz donguye sokucaktir

``` python
    i = 0
    while True:
        # Bu kod blogu "sonsuza kadar" calisicak.
        prtin(i) 
        i += 1
```


## __For Loop :__

`for` döngüsü, (bir liste, bir demet, bir sözlük, bir küme veya bir string) üzerinde yineleme yapmak için kullanılır.

Print each fruit in a fruit list:
```python
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
```


### __Looping Through a String__

Loop through the letters in the word "banana":

```python
for x in "banana":
print(x)
```

### __The `break` Statement__
Exit the loop when x is "banana":
```python
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
  if x == "banana":
    break
```

### __The `continue` Statement__
Do not print banana:
```python
fruits = ["apple", "banana", "cherry"]
for x in fruits:
  if x == "banana":
    continue
  print(x)
```

### __The `range()` Function__
```python
for x in range(6):
  print(x) 
```

sing the start parameter:
```python
for x in range(2, 6):
  print(x)
```

### __`else` in `for` Loop__
The `else` keyword in a `for` loop specifies a block of code to be executed when the loop is finished:


Print all numbers from 0 to 5, and print a message when the loop has ended:
```python
for x in range(6):
  print(x)
else:
  print("Finally finished!") 
```