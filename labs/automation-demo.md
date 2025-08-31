# Lab – Automation Demo

## Objective
Run a basic automated test script in Selenium.

## Instructions
1. Install Selenium for Python.  
2. Write a script to open a website (e.g., https://example.com).  
3. Verify the page title contains "Example".  

## Example
```python
from selenium import webdriver

driver = webdriver.Chrome()
driver.get("https://example.com")

assert "Example" in driver.title
driver.quit()
```

## Deliverable

- Script file (test_demo.py) and screenshot of successful run.
