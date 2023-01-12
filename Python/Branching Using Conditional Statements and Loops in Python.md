What is Branching
	The abilities to make decisions and execute sets of statements based on if one or more conditions are true. 


# Statements Vs Expressions
> Statements: Instructions that can be executed. Anything that can appear on the right side of `=`. 

> Expressions: Some code that evaluate to a value. Most expressions can be executed as statements. But *Not all statements are expressions*. 
# If Statements 
#Synthax
```python
if condition:
	statement 1
	statement 2
```

#synthaxMeaning
+ condition can be value, variable or expression.
+ If condition is `True` then the statements within the block are executed 


#### Shorthand writing If statements
#Synthax 
```python
x = true_value if condition else false_value
```

#Example  Showing shorthand and non boolean conditions
```python
Number = 13

parity = 'even' if Number % 2 == 0 else parity = 'odd'
```
# Else Statements 
#Synthax 
```python
if condition:
	statement 1
	statment 2
else:
	statement 4
	statement 5
```

#synthaxMeaning 
+ If condition  is `True`, then statements in `if` block is ran.
+ If condition is `False`, Then statments in `else` is ran. 

# Elif Statements 
Elif = else if 

#Synthax 
```python 
if condition1: 
	statement 1 
elif condition2:
	statement 2
elif condition3:
	statement 3
elif condition4:
	statement 4
elif condition5:
	statement 5
```

#synthaxMeaning 
+ If condition1 is `True`, then run statement1
+ If condition1 is `False`, then run the `else` condition2. 
+ If the `else` condition2 is true, then run the statement2.
+ Repeat until the first `True` statement is achieved. 
+ One first `True` condition is achieved, all remaining conditions are not evaulated 


# Combining if, elif and else 
#Example
```python

Number = 49

if Number % 2 == 0: #Condition1
	print('{} is divisible by 2' .format(Number))

elif Number % 3 == 0: #Condition2
	print('{} is divisible by 3' .format(Number))
elif Number % 5 == 0: #Condtion3
	print('{} is divisible by 5' .format(Number))

else:
	print('{} is not divisible by 2,3 or 5'.format(Number))
```

#synthaxMeaning 
+ Variable named `Number` has a value of `49`
+ If Condition 1 is True then run the print statement
+ If Condition 1 is False then assess if condition 2 is true
+ If Condition 2 is True then run the statement
+ If Condition 2 is False then assess if condition 3 is true and so on.
+ If all Conditions is False then run the else statement.


# Nested Conditional Statements 
#Synthax 
```python 

if condition 1: 
	statement 1
	if condition 2:
		statement 2 
	else:
		statement 3
else:
	statement 4
	if condition 3:
		statement 5
	else:
		statement 6
```

#synthaxMeaning 
+ If Condition 1 is True
	+ Statement 1 will run 
	+ Condition 2 will be assessed like a regular if statement
	+ Output: Statement 1 + Statement 2 OR Statement 3
+ If Condition 1 is False
	+ Statement 4 will run 
	+ Condition 3 will be accessed like a regular if statment
	+ Output: Statement 4 + Statement 5 OR Statement 6


![[Mind Map - IF, ELIF, ELSE statements 1.jpeg]]


# Pass Statements 
#Synthax 
```python
if condition 1:
	pass
elif condition 2:
	statement 1
```

#Usage
`if` statements cannot be empty and as such will require a `pass` statement to avoid any errors




