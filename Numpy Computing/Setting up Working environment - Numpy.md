
#### Installing Numpy in Python #InstallinPython

^84363a

``` python
!pip install Numpy -- upgrade -- quiet 

```


#### Loading Numpy Module #LoadingModulePsy 

```python

import numpy as np
```

^c6d545



## Working with CSV Files #CSVPython

**Importing Local  CSV file**
```Python
data = np.genfromtxt('file_name_of_choice.txt', delimiter = ',', skip_header=1)
```

**Importing Online CSV file**
```python
#Python Module that makes working with URL easier 
import urllib.request 

#To retrieve url
urllib.request.urlretrieve( 'url' , 'file_name_of_choice' ) 
 
```


**Saving CSV file after modifications**
```python

#fmt = decimal points | default = 10 | %.2f = 2  
np.savetxt('Desired_Name.txt', array_name, fmt ='%.2f', header = 'column1,column2,column3...', comments=' ')


```
