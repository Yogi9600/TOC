# Experiment 29: Design and Simulation of a Turing Machine (TM) Using Simulator

## Aim

To design and simulate a Turing Machine (TM) using a simulator to perform string comparison where w={aba aba}.

---

## Problem Statement

Design a TM to check if two strings separated by a blank or a marker are identical.

---

## Theory

A TM can compare two strings by reading the first character of the first string, marking it, moving to the start of the second string, verifying the character matches, marking it, and returning to the next unmarked character of the first string. This repeats until all characters are matched.

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

The TM successfully compares strings and accepts when they are identical.

---

## Conclusion

The Turing Machine was successfully designed and simulated. It correctly identifies valid strings, demonstrating the practical implementation of Turing machines using simulation software.

---

## Output

![Output](EXP%2029%20-%20Output.png)
