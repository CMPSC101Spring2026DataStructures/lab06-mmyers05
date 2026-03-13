# CS101 Spring 2026 — Practice Midterm Reflection

Name: Magnolia Myers
Date: 3/13/2026

After completing the practice test, please reflect on your experience by
answering the questions below. Replace each `TODO` with a thoughtful response
(a few sentences each). Your responses help you consolidate what you learned
and identify areas to review before the real midterm.

---

## 1. Self-Assessment

**Question:** How did you feel about your performance on the practice test?
Which topics felt most comfortable, and which ones felt most difficult?

**Your Answer:**

I think I did pretty well on the practice test. I had the most difficulty with things like lambda functions and classes.

---

## 2. Tricky Questions

**Question:** Identify one question you got wrong (or were unsure about).
Explain the concept being tested and describe why the correct answer is right.

**Your Answer:**

One question that I was unsure about was 18, which was the lambda function. The correct answer is right because 3 is less than 7, so they are added to get 10. 

---

## 3. Loops and Iteration

**Question:** In your own words, explain the difference between `range(a, b, step)`
with a positive step versus a negative step. Give one original example of each.

**Your Answer:**

A postive step increases the numbers, and the negative step decreases it. A positve step in range(1, 10, 3) would give 1, 4, 7. A negative step in range (10, 1, 2) would give 10, 8, 6, 4, 2.

---

## 4. Data Structures

**Question:** Python has lists, tuples, dictionaries, and sets. Describe one key
difference between a list and a tuple, and one key difference between a
dictionary and a set. When would you choose each?

**Your Answer:**

A list and tuple are different because tuples cannot be changed and lists can. Dictionaries and sets are different because a dictionary stores paired items with keys and values, while sets are just lists. They also don't allow for duplicates. Lists would be useful if you have a lot of data. Tuples would  be useful for fixed constants. Dictionaries would be useful if you have two things that need to stay together, like city and city name. Sets would be useful if you need to remove dupliates from something. 

---

## 5. Functions

**Question:** What is a default parameter in a Python function? Write a short
example function that uses a default parameter, and explain what happens when
the caller omits that argument.

**Your Answer:**

A default parameter in a Python function is something that is set so that if something isn't called in a function, the program still works. For example if you used a function to greet people that asked for name, and name was not entered, then it could return something like "Hello Guest" instead. 

---

## 6. List Comprehensions

**Question:** List comprehensions can include an optional filter condition.
Rewrite the following traditional loop as a list comprehension:

```python
result = []
for n in range(1, 11):
    if n % 3 == 0:
        result.append(n * 2)
```

**Your Answer:**

result = [x*2 for x in range(1, 11) if x%3 == 0]

---

## 7. Operator Precedence

**Question:** Python evaluates `**` (exponentiation) right-to-left.
What is the value of `2 ** 2 ** 3`? Show your step-by-step reasoning.

**Your Answer:**

2^3 is 8, and 2^8 is 128. 

---

## 8. Classes 

**Question:** What are classes in Python programming? Explain why they are necessary in programming.

**Your Answer:**

TODO

---

(Did you remember to add your name and date at the top of this document?)
