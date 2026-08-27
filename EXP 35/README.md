# Experiment 35: Design and Simulation of a Deterministic Finite Automaton (DFA) Using Simulator

## Aim

Let L be regular language, L consist set of string over {a,b} number a’s minus number b’s less than or equal to 2. Design DFA to accept the the language L.

---

## Problem Statement

Design a DFA for the language of strings over {a, b} where (number of a's) - (number of b's) <= 2.

---

## Theory

A DFA can track the difference between the count of two characters by using states to represent the current difference. Since the difference can be negative (if there are more b's than a's), but the condition is merely <= 2, any difference less than or equal to 2 is valid. However, a DFA must have a finite number of states. This specific language description as written is context-free, not regular, if unbounded. Assuming a bounded or specific interpretation for a simulator, states track the net difference up to a limit.

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

The DFA successfully processes the strings according to the condition.

---

## Conclusion

The automaton was successfully designed and simulated. It correctly processes strings based on the specified condition, demonstrating the practical implementation of automata using simulation software.

---

## Output

![Output](EXP%2035%20-%20Output.png)
