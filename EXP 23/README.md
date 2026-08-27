# Experiment 23: Design and Simulation of a Turing Machine (TM) Using Simulator

## Aim

To design and simulate a Turing Machine (TM) using a simulator to accept the input string Palindrome bbabb.

---

## Problem Statement

Design a TM for the language of palindromes over {a, b} specifically accepting the string 'bbabb'.

---

## Theory

A Turing Machine can check for palindromes by comparing the first and last characters of a string. It reads the first character, replaces it with a blank, moves to the end, verifies the last character matches, replaces it with a blank, and moves back to the start. This process repeats until all characters are matched or an isolated center character is found.

---

## Input Alphabet

```
Σ = {a, b}
```

---

## Procedure

1. Open the simulation software.
2. Create the required states.
3. Mark the initial state.
4. Mark the accepting state(s).
5. Add the transitions (read, write, move direction).
6. Save the machine.
7. Test the machine using different input strings.
8. Verify whether the strings are accepted or rejected.

---

## Result

The TM successfully accepts palindrome strings like 'bbabb'.

---

## Conclusion

The Turing Machine was successfully designed and simulated. It correctly identifies valid palindromes, demonstrating the practical implementation of Turing machines using simulation software.

---

## Output

![Output](EXP%2023%20-%20Output.png)
