# Experiment 28: Design and Simulation of a Pushdown Automaton (PDA) Using Simulator

## Aim

To design and simulate a Pushdown Automaton (PDA) using a simulator to accept the input string a^n b^n.

---

## Problem Statement

Design a PDA for the context-free language L = {a^n b^n | n >= 1}.

---

## Theory

A PDA uses a stack to match elements. For this language, the PDA pushes a symbol (e.g., 'A') onto the stack for every 'a' it reads. Once it starts reading 'b's, it pops an 'A' for every 'b'. If the stack becomes empty exactly when the input ends, the string is accepted.

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
5. Add the transitions (read input, pop stack, push stack).
6. Save the automaton.
7. Test the automaton using different input strings.
8. Verify whether the strings are accepted or rejected.

---

## Result

The PDA successfully accepts strings of the form a^n b^n.

---

## Conclusion

The PDA was successfully designed and simulated. It correctly identifies valid strings, demonstrating the practical implementation of pushdown automata using simulation software.

---

## Output

![Output](EXP%2028%20-%20Output.png)
