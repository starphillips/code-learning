
strings can be `"" ''`


You can change types and variables in Python

Examples:

``` python
age = 8
age = "eight"
```

``` python
'5' + '4' = 54
```

``` python
price = "9"
total = price * 5

# output: 99999
```

#### String Indexing
``` python
msg = 'I love cats'
msg[0]
>> I

msg[3]
>> o
```

![[Pasted image 20260920164347.png]]
Works backwards as well - use for last character of the string

#### String Slices
``` python
msg = 'I love cats'
msg[2:7] # up to but NOT INCLUDING 6
>> love c

msg[3:99] # goes to the end of the string even if its not that long
ms[3:] # does the same
>> love cats 

ms[:5]
>> I love

msg = 'ha!ha!ha!ha!'
msg[0:10:2] # extra is the step i.e. skip 2 
>> hhhh

# start:stop:step
```
