# Exercism - Daily Problem 001: Hello, World!

## Solution Overview:
- SQL (Structured Query Language) is not a scripting language like PowerShell or Batch scripting. Nor is it a general purpose object-oriented programming language like Java.
- It is simply a query language as it's name suggests, used for database managament applications.
- Thus here, we aren't printing or returning any value.
- We are pushing the value "Hello, World" into the column `greeting` in table `hello_world`.
- The evaluator script simply checks if what we inserted into the table is the correct value.

## Solution Code:
```sql
INSERT INTO
  hello_world (greeting)
VALUES
  ('Hello, World!');
```

## Conceptual Output:
```
 greeting
__________

Hello, World!
```
The value has been inserted into a row in the column `greeting` in the table `hello-world`.