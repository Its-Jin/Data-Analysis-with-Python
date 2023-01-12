What is While Looops
	Provides the ability to run statements numerous times 

#Synthax 
```python 

while condition 1:
	statement(s)
```

#Usage 
The statements in the while loop will continue to run as long as condition 1 remains True 
Generally, one of the statements under the while loop will render the condition false 

#Example 
```python 
result = 1 
i = 1

while i <=100
	result = result * i
	i = i + 1

print("the factorial of 100 is {}" .format(result))
```
#synthaxMeaning 
+ Starting variables `result` and `i` contain values of `1`
+ when `i` is less than or equal to 100, the new `result` value will be previous `result` value * i and new `i` value will be old `i` +1 
NOTE: Factorial of a whole Number is the function that multiplies the number by every natural number below it. 

#FunCoding
Creating patterns with while loops 
```python
line = ''
max_length = 10

while len(line) < max_length:
	print(line)
	line += '*'

while len(line) > 0:
	print(line)
	line = line[:-1]
```


# Infinite Loops and Breaking them 

