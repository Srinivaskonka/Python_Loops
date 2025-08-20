# Python Loops 

This repository contains examples and explanations of **loops in Python**.  
Loops are used to execute a block of code multiple times efficiently.

---

## 🔄 Types of Loops in Python

### 1. **for loop**
Used for iterating over a sequence (list, tuple, string, range, etc.).

```python
# Example: Print numbers from 1 to 5
for i in range(1, 6):
    print(i)
```
### 2. **while loop**
Executes a block of code as long as the condition is True.
#### Example: Print numbers from 1 to 5
```python
i = 1
while i <= 5:
    print(i)
    i += 1
```
 Loop Control Statements
break
Stops the loop prematurely.
```python
for i in range(1, 10):
    if i == 5:
        break
    print(i)
````
###  continue
##### Skips the current iteration and moves to the next.
``` python
for i in range(1, 6):
    if i == 3:
        continue
    print(i)
```
### else with Loops
#### else runs if the loop completes without break.
```python
for i in range(1, 4):
    print(i)
else:
    print("Loop finished!")
```
