### π€ **Quize1 : μ€λ ₯ νμ€νΈ** 

(1) print(len("95637+12")) κ° μΆλ ₯νλ κ°μ? = **8**



(2)μλμ μ½λλ₯Ό νμΈνμΈμ. κ²°κ³Όλ‘ μΆλ ₯λλ κ°μ λ¬΄μμΌκΉμ? = **C**

```python
score = 67
if score < 80 and score > 70:
    print("A")
elif score < 90 or score > 80:
    print("B")
elif score > 60:
    print("C")
else:
    print("D")
```



(3) μ½μμ μΆλ ₯λλ κ°μ λ¬΄μμΌκΉμ? = **NameError**

```python
def a_function(a_parameter):    
    a_variable = 15    
    return a_parameter 
a_function(10)
print(a_variable)
```



(4) μΆλ ₯λλ κ°μ λ¬΄μμΌκΉμ?  = **15**

```python
def outer_function(a, b):
    def inner_function(c, d):
        return c + d
    return inner_function(a, b)
 
result = outer_function(5, 10)
print(result)
```



(5) `Car` ν΄λμ€μ μμ±κ³Ό λ©μλλ λ€μκ³Ό κ°μ΅λλ€. λ΅λ³μμ μ€λ₯κ° λ°μνλ μ½λλ λ¬΄μμΌκΉμ?

**= car.break = 0**

**Attributes:**

```python
num_of_seats
speed
```

**Methods:**

```python
drive()
break()
```



(6) `my_toyota` μ `my_fiat` λ₯Ό μ€λͺνλ λ¨μ΄λ λ¬΄μμΌκΉμ? = **κ°μ²΄ object**

```python
my_toyota = Car()
my_fiat = Car()
```



(7) **main.py** νμΌμμ μ½λλ₯Ό μμ±ν΄ **quiz.txt** νμΌμ μ¬λ κ²½μ° **μλ** νμΌ κ²½λ‘λ λ¬΄μμΌκΉμ?

**= "quiz.txt"**

![image-20220729004913849](Quize1.assets/image-20220729004913849.png)



(8) μλμ μ½λκ° μΆλ ₯νλ κ°μ λ¬΄μμΌκΉμ? = **20, 4, 12**

```python
def foo(a, b=4, c=6):
    print(a, b, c)
 
foo(20, c=12)
```



(9) μμ μ½λκ° μΆλ ₯νλ κ°μ λ¬΄μμΌκΉμ?

= **4 (7, 3, 0) {'x':10, 'y':64}**

```python
def all_aboard(a, *args, **kw): 
    print(a, args, kw)
 
all_aboard(4, 7, 3, 0, x=10, y=64)
```



(10) λ€μ μ½λκ° μΆλ ₯νλ κ°μ λ¬΄μμΌκΉμ? μ»΄ν¨ν°λ‘ κ³μ°ν  νμλ μμ΅λλ€.

```python
numbers = [1, 1, 2, 3, 5, 8, 13, 21, 34, 55]
result = [num + 3 for num in numbers if num % 2 == 0]
print(result)
```

 = **[5, 11, 37]**

