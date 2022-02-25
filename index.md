# CSE Notes Feb 16

Lecture notes about If Statements and For Loops

**If Statements**

Extending the entry example to have 3 (or more) outcomes based on the age

-less than 12 - no entry

-12 - 17 - waiting list

-18 or older - welcome

---

name = input()
age = int(input())

if age < 12:
    print ("No entry")



elif age >= 12 and age < 18:
    print ("Waiting List")

print("Hello")

if age >= 18:
    print ("Welcome")'
    
---
