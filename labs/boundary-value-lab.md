# Lab – Boundary Value Analysis

## Objective
Apply boundary value analysis (BVA) to identify test cases.

## Scenario
A login system allows usernames of length **3 to 12 characters**.

## Tasks
1. Identify valid and invalid boundary values.  
2. Design test cases for edge conditions.  
3. Execute the cases manually or with automation.  

## Example
- Test "ab" → invalid (too short).  
- Test "abc" → valid (minimum).  
- Test "abcdefghijkl" → valid (maximum).  
- Test "abcdefghijklm" → invalid (too long).
