# Lab – Unit Testing Basics

## Objective
Learn how to design and run simple unit tests for small code functions.

## Instructions
1. Choose a simple function (e.g., add two numbers).  
2. Write test cases for normal, boundary, and invalid inputs.  
3. Run the tests using a framework like **JUnit** (Java) or **PyTest** (Python).  

## Example (Python)
```python
def add(a, b):
    return a + b

def test_add():
    assert add(2, 3) == 5
    assert add(-1, 1) == 0
    assert add(0, 0) == 0
```
## Deliverable

- Test report with results (pass/fail).
