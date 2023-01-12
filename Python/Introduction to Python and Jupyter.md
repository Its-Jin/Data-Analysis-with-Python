
# Basic Arithmetic Operations #ArithmeticPython
Python supports the following arithmetic operators:
| Operator | Purpose | Example | Result |
|------------|-------------------|-------------|-----------|
| `+` | Addition | `2 + 3` | `5` | 
| `-` | Subtraction | `3 - 2` | `1` |
| `*` | Multiplication | `8 * 12` | `96` | 
| `/` | Division | `100 / 7` | `14.28..` | 
| `//` | Floor Division | `100 // 7` | `14` |
| `%` | Modulus/Remainder | `100 % 7` | `2` | 
| `**` | Exponent | `5 ** 3` | `125` | 


# Evaluating Conditions 
| Operator | Description | 
|-------------|-----------------------------------------------------------------| 
| `==` | Check if operands are equal |
| `!=` | Check if operands are not equal | 
| `>` | Check if left operand is greater than right operand |
| `<` | Check if left operand is less than right operand |
| `>=` | Check if left operand is greater than or equal to right operand |
| `<=` | Check if left operand is less than or equal to right operand | 


# Combining conditions with Logical Operators

#### And Operators 
| `a` | `b` | `a and b` | 
|---------|--------|-----------|
| `True` | `True` | `True` | 
| `True` | `False`| `False` |
| `False`| `True` | `False` | 
| `False`| `False`| `False` |


#### Or Operators
| `a` | `b` | `a or b` |
|---------|--------|-----------|
| `True` | `True` | `True` |
| `True` | `False`| `True` |
| `False`| `True` | `True` |
| `False`| `False`| `False` |


# Data Types  

| **DataType**  |  **Description** |  
|---|---|
| Integer  |  +ve or -ve whole numbers |   
| Float |  Numbers with decimal point Examples: 4.0, 3.99, 1e-2 |  
| Boolian  | True (1) and False (0) outputs that is the result of a comparison function| 
| None  |  Used to indicate the absence of a value |
| String   | text which must be contained within quotations |
| List  | `[]`  |
| Tuple | ( ) |


# Common Fuctions for DataTypes


| Usage | Syntax | 
|-------|--------|
|Gives the datatype| `type(var)`|
|Turn float into an integer| `int(float)`|
|Turn datatype into a Bool | `bool(var)`|



# Common Functions in Strings 
| Usage | Syntax |  Example |
|-------|--------|----------|
| Length | `len(var)` | |
| Indexing string - showing the letters within the range of index | `Var[x:y]`| |
| Joining strings | `string 1 + string 2` | |
| Changing cases | `.lower()` , `.upper()`, `.capitalize()` | |
| Replaces strings with other strings | `.replace` |  `varNew = varOld.replace("ABC", "CBA")` |
| Splitting a string into a list of characters | `.split()`||
| Remove spaces from beginning and end of the string | `.strip()`||
| Inserts specified variable output in designated { } | `.format()` ||






# Common Functions in Lists

| Usage | Syntax | Example |
|-------|--------|----------|
| Creating a List | `list = [x,y,z]`| |
| Indexing a list | `list[value_location]`||
| Modifying value within a list | `list[location] = "new value"` ||
| Adding a value to the list | `.insert(location, "new value")` ||
| Remove a specified value from the list | `.remove('value')`||
| Adding new value at the end of the  list | `.append('new value')` ||
| Removing the value from the specified location of a list | `.pop(location)` ||
| Examining if a value exists within a list | `'Value Name' in List Name` ||
| Combining Lists | `+` ||
| Copying a list | `.copy` ||

# Common Functions in Tuples 
What is a Tuple
	A list that cannot be modified, change, apend, or remove list items

# Common Functions in Dictionary 
What is a dictionary 
	Unordered collection of items where each item is stored as a key with a value. Often used to store multiple details of a single variable
| Usage | Syntax | Example |
|-------|--------|----------|
| Creating a dictionary | `varA{ } ` | `Person { 'name' : 'John', 'sex' : 'male' }`|
| Another way to create a dictionary |  `varA = dict( )` | ` dict1 = dict(name=Jane, sex=female)`|
| How to access keys | `dict['key name']` | `dict['name']` | 
| Check if Key exists in a dictionary | `in` | `name in dict` |
| Changing Values within a Key | `=New Value` | `dict['name'] = James | 
| Examining all keys associated with a dictonary | `.keys( )` | `dict.keys( )` |
| Examining all values associated with a dictonary | `.values( )` | `dict.values()`|




