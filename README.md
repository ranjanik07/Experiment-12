# Experiment-12
## Pytest Python program for Addition
# Aim:
To write a Python program using Pytest for testing the addition of two numbers.
# Algorithm: 
Start the program.

Define a function add(a, b) inside EX12.py that returns the sum of two numbers.

Create a separate test file TEST_EX12.py.

Import the add function from EX12.py into the test file.

Write test cases using assert statements to check correctness.

Run the test using: (-s for stdout to get to display the print statements)
```
ppytest -s TEST_EX12.py
```
If all tests pass, the program is correct.
# Program:
EX12.py
```
def add(a, b):
    return a + b
```
TEST_EX12.py
```

from EX12 import add

def test_addition():
    
    print()
    
    print("add(2, 3) =", add(2, 3))      
    assert add(2, 3) == 5

    print("add(-1, 1) =", add(-1, 1))     
    assert add(-1, 1) == 0

    print("add(0, 0) =", add(0, 0))     
    assert add(0, 0) == 0

    print("add(10, -5) =", add(10, -5))   
    assert add(10, -5) == 5
```
# Output
<img width="1073" height="297" alt="image" src="https://github.com/user-attachments/assets/7f277622-f69f-461f-8fe5-b51e1664a761" />

# Result
Thus, the Pytest program for Addition (EX12 & TEST_EX12) was successfully written, executed, and tested. ✅
