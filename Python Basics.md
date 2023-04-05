# Python Basics
---

## Data Types

---

### 1. Fundamental Data Types:
| ***Data Type*** |          ***Function***          |
|:---------------:|:--------------------------------:|
|       int       |     used for integer numbers     |
|      float      |     used for decimal numbers     |
|      bool       | used for true or false statement |
|   str(string)   | used for strings and characters  |
|      list       |                                  |
|      tuple      |                                  |
|       set       |                                  |
|      dict       |                                  |

---

#### Math Functions

```python
print (round(3.1)) #round down for the most near integer number
print (round(5.9)) #round up for the most near integer number
print (abs(-20)) #Absolute value(+ve only)
print (bin(5)) #Convert to Binary number
print (int('0b101' , 2)) #Convert to Decimal
```

---

#### Operator precedence

```python
print ((20 - 3) + 2 ** 2)  # 17 + 4 = 21
#  ()
#  **
#  * /
#  + -
```

---

#### Variables
Variables are ways for us to store information on our computer and programs. So we can hold perhaps user inputs like values.

There is specific rules that Python has as a whole:
1. snake_case
2. Starts with lowercase or underscore
3. Letters, Numbers, underscores
4. Case sensitive
5. Don't overwrite keywords

---

```python
user_iq = 190 #snake_case & starts with lowercase
_maxiq = 300 #starts with underscors
user4_iq = 220 #include numbers
user_IQ = 280 #case sensitive != user_iq
print (user_iq, user_IQ , _maxiq , user4_iq)


user_age = user_iq/4
age = user_age #assign variable to another variable
print (age)

PI = 3.14 #Constants

a,b,c = 1,2,3 #rapidly assign value to variable
print (c , a , b)
```

---
#### Expression VS Statements

**Expression**: is a piece of code that produces a value.
**Statement**: on the other hand is an entire line of code that preforms some kind of action.

```python
iq = 100
user_age = iq/5 #(iq/5) is an expression
				#(user_age = iq/5) is a statement
```

---
#### Augmented assignment operator

```python
value = 5
value = value + 2 #OLD way
value += 5 # Augmented assignment operator
value -= 2
value *= 2

print (value)
```

---

#### int/float
```python
print (type(2+4)) #int
print (type(2/4)) #float
print (type(0))
print (type(9.9+1.1)) 
print (2 ** 3) # n1 Power of n2
print (5 // 4) #Round Down the number
print (6.5 % 4) #Modules
```

---



---

### 2. Classes (Custom) Data Types:


---

### 3. Specialized Data Types:
