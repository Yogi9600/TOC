# Experiment 24: Design and Simulation of a Turing Machine (TM) Using Simulator

## Aim

To design and simulate a Turing Machine (TM) using a simulator to accept the input string wcw.

---

## Problem Statement

Design a TM for the language of strings of the form wcw, where w is a string over {a, b} and c is a separator.

---

## Theory

A Turing Machine checks the wcw pattern by reading a character before 'c', marking it, moving past 'c' to find the corresponding unmarked character, verifying it matches, marking it, and returning to the start. It repeats this until all characters before 'c' are matched with characters after 'c'.

---

## Input Alphabet

```
Σ = {a, b, c}
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

The TM successfully accepts strings of the form wcw.

---

## Conclusion

The Turing Machine was successfully designed and simulated. It correctly identifies valid strings, demonstrating the practical implementation of Turing machines using simulation software.

---

## Output

![Output](EXP%2024%20-%20Output.png)
