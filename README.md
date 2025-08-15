# MyPythonLearnings
my python learnings from august 2024 to august 2025

# What I have learnt in Python so far

## **Print Statements**

The most basic thing in all of Python, and how you communicate with the user.

#### **Basic Print Statement**

print('Hello world')

#### **F Strings**

print(f'There are {number} people here.')

## Variables

##### You need this when a value is constantly changing throughout your code. 

#### Defining Variables

my_variable = contents_of_my_variable

#### Appending to variable

my_variable += what_you_want_to_add

## **Converting Data Types**

##### Useful if certain commands only support certain data types. 

#### List of All Types

String --> str() or (' ')

Integer --> int() or xx

Float --> float()

List --> list() or [ ]

#### List Comprehensions

##### Shorter way to write a for loop within a list. 


new_list = [expression **for** item **in** iterable **if** condition]


Tuple --> tuple() or ( )

Sets --> set() or { }

Dictionary --> dict() or { }

## Loops

##### Instead of rewriting the same code over and over, or if you want to test several things, you can use a loop to 'loop' the same code over and over. 

### 'For' Loops

**for** your_variable **in** number_or_argument **:**
    
    line 1

    line 2

    line 3

    line ...
    
### While Loops

**while** your_condition **:**
    
    line 1

    line 2

    line 3

    line ...

## Functions

##### Shortens the amount of code you have to write and the amount you have to tweak if an error happens. 

#### Syntax

def your_function(argument, optional argument):

    line 1

    line 2

    line 3

    line ...

    return argument (optional)
#### Calling the Function

your_function(argument, optional argument)

## Regex

##### Searches through a large text file to find specific patterns such as email addresses or phone numbers. ADD FUNCTION CHARACTERS AND METHODS

<table border="1" cellpadding="5" cellspacing="0">
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
    <th>Header 3</th>
  </tr>
  <tr>
    <td>Row 1 Col 1</td>
    <td>Row 1 Col 2</td>
    <td>Row 1 Col 3</td>
  </tr>
  <tr>
    <td>Row 2 Col 1</td>
    <td>Row 2 Col 2</td>
    <td>Row 2 Col 3</td>
  </tr>
</table>



## Web Scraping

##### Scrapes a website for desired content like a specific table or data. 

from bs4 import BeautifulSoup

import pandas as pd

import requests

url = 'https://google.com'
page = requests.get(url)

soup = BeautifulSoup(page.text, 'html.parser')

table = soup.find_all('what_you_are_looking_for')

...

## Terminal Commands

##### Quick ways to do tasks from the terminal app and very useful for computers without a screen. 

