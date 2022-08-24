# pythonscript

#Question 1
```python
#A python command for numbers which are divisible by 7 and multiple 0f 5

nl=[]
for x in range(1500, 2701):
    if (x%7==0) and (x%5==0):
        nl.append(str(x))
print (','.join(nl))
```

#question 2
```python
# Python program to find the factorial of a number provided by the user.

# change the value for a different result
num = 7

# To take input from the user
#num = int(input("Enter a number: "))

factorial = 1

# check if the number is negative, positive or zero
if num < 0:
   print("Sorry, factorial does not exist for negative numbers")
elif num == 0:
   print("The factorial of 0 is 1")
else:
   for i in range(1,num + 1):
       factorial = factorial*i
   print("The factorial of",num,"is",factorial)
```

#Question 3
```python
e = dict()
n = 5
for c in range(1,n+1):
    e[c]= c**2
print(e)    
```

#Question 4
```python
f = ['2', '3', '4', '4']
print(f)
print(tuple(f))
```

#question5
```python


```
