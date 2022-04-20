# Introduction to Python
## Python Basics
An introduction to the basic concepts of Python. Learn how to use Python interactively and by using a script. Create your first variables and acquaint yourself with Python's basic data types.
### The Python Interface
- Experiment in the IPython Shell; type `5 / 8`, for example.
- Add another line of code to the Python script on the top-right (not in the Shell): `print(7 + 10)`.
- Hit *Submit Answer* to execute the Python script and receive feedback.
```python
# Example, do not modify!	
print(5 / 8)

# Print the sum of 7 and 10
print(7 + 10)
```
### When to use Python?
**Possible Answers**
- [ ] You want to do some quick calculations.
- [ ] For your new business, you want to develop a database-driven website.
- [ ] Your boss asks you to clean and analyze the results of the latest satisfaction survey.
- [x] All of the above.
### Any comments?
Above the `print(7 + 10)`, add the comment `# Addition`
```python
# Division
print(5 / 8)

# Addition
print(7 + 10)
```
### Python as a calculator
Suppose you have $100, which you can invest with a 10% return each year. After one year, it's <math xmlns="http://www.w3.org/1998/Math/MathML"><mn>100</mn><mo>&#xD7;</mo><mn>1.1</mn><mo>=</mo><mn>110</mn></math> dollars, and after two years it's <math xmlns="http://www.w3.org/1998/Math/MathML"><mn>100</mn><mo>&#xD7;</mo><mn>1.1</mn><mo>&#xD7;</mo><mn>1.1</mn><mo>=</mo><mn>121</mn></math>. Add code to calculate how much money you end up with after 7 years, and print the result.
```python
# Addition, subtraction
print(5 + 5)
print(5 - 5)

# Multiplication, division, modulo, and exponentiation
print(3 * 5)
print(10 / 2)
print(18 % 7)
print(4 ** 2)

# How much is your $100 worth after 7 years?
print(100 * 1.1 ** 7)
```