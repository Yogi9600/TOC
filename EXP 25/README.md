# Experiment 25: Design and Simulation of a Deterministic Finite Automaton (DFA) Using Simulator

## Aim

To design and simulate a Deterministic Finite Automaton (DFA) using a simulator to accept the string even number of a’s and odd number of b’s.

---

## Problem Statement

Design a DFA for the language of strings over {a, b} containing an even number of 'a's and an odd number of 'b's.

---

## Theory

A DFA can track multiple parity conditions simultaneously by using states that represent combinations of parities. In this case, 4 states are needed: (even a, even b), (even a, odd b), (odd a, even b), and (odd a, odd b). The state (even a, odd b) is the accepting state.

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
5. Add the transitions according to the requirement.
6. Save the automaton.
7. Test the automaton using different input strings.
8. Verify whether the strings are accepted or rejected.

---

## Result

The DFA successfully accepts strings with an even number of a's and an odd number of b's.

---

## Conclusion

The automaton was successfully designed and simulated. It correctly accepts the specified valid strings and rejects all invalid strings, demonstrating the practical implementation of automata using simulation software.

---

## Output

![Output](EXP%2025%20-%20Output.png)
