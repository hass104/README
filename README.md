# Logical Equivalence Checker


# Overview
This project is a Java application that checks if two compound propositions are logically equivalent. The program evaluates both propositions by generating their truth tables and compares the truth values for all possible combinations of variables (A, B, C). Logical operators (AND, OR, NOT) and parentheses are supported.

# Code breakdown
evaluate Method:
This evaluates basic logical expressions without parentheses.
It processes NOT (!) first, then handles AND (&) and OR (|) operators.

evaluateWithParentheses Method:
This handles expressions with parentheses.
It evaluates the innermost parentheses first and replaces them with the result, eventually evaluating the entire expression.

generateTruthTable Method:
It creates the truth table for a proposition by going through all possible combinations of A, B, and C (True or False).
It shows the result for each combination.

checkEquivalence Method:
This compares two propositions by evaluating both for all combinations of A, B, and C.
If the results match for all combinations, the propositions are logically equivalent.

main Method:
This collects two logical propositions from the user.
It generates truth tables for both and checks if they are logically equivalent, then prints the result.


# How the Program Works
The program works by evaluating logical expressions based on the truth values of the variables A, B, and C. It handles parentheses(EX: (A|B)) For each combination of A, B, and C, the program computes the result for both propositions and checks if they match.

# Input
The user provides two logical propositions as input.

propositions should involve the variables A, B, C and the logical operators & (AND), | (OR), ! (NOT), and parentheses ().
if any other charcter entered the program will stop working

DO not add any spaces between characters( EX: (EX: (A|B))


# Input Screenshot:
if you input (A&B)|C and (A|!B)&C this how input display

![image](https://github.com/user-attachments/assets/13428409-976b-488c-b41a-db389740d3c5)

# Output
The program generates and displays the truth tables for both propositions.
It outputs whether the two propositions are logically equivalent or not.

#Output Screenshot:
the output for (A&B)|C and (A|!B)&C this what the the truth tables display and they wont be Equivalant

![image](https://github.com/user-attachments/assets/07cd9914-b079-4f87-9c2a-a95a569a3f3a)




