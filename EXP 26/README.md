# Experiment 26: Design and Simulation of a Deterministic Finite Automaton (DFA) Using Simulator

## Aim

To design and simulate a Deterministic Finite Automaton (DFA) using a simulator to accept the input string “bc”, “c”, and “bcaaa”.

---

## Problem Statement

Design a DFA for the finite language L = {"bc", "c", "bcaaa"}.

---

## Theory

A DFA for a finite set of strings can be constructed by building a trie-like structure representing all valid paths. Paths that lead to fully formed strings in the language end in accepting states. Any deviation from valid prefixes leads to a dead state.

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
5. Add the transitions according to the requirement.
6. Save the automaton.
7. Test the automaton using different input strings.
8. Verify whether the strings are accepted or rejected.

---

## Result

The DFA successfully accepts specifically "bc", "c", and "bcaaa".

---

## Conclusion

The automaton was successfully designed and simulated. It correctly accepts the specified valid strings and rejects all invalid strings, demonstrating the practical implementation of automata using simulation software.

---

## Output

![Output](EXP%2026%20-%20Output.png)
