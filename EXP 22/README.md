# Experiment 22: Design and Simulation of a Deterministic Finite Automaton (DFA) Using Simulator

## Aim

To design and simulate a Deterministic Finite Automaton (DFA) using a simulator to accept the string start with a or b over the set {a,b}.

---

## Problem Statement

Design a DFA for the language of strings over {a, b} starting with 'a' or 'b'.

---

## Theory

A DFA can verify the starting character of a string. Since the alphabet is {a, b}, any non-empty string will start with either 'a' or 'b'. Thus, the DFA simply needs to accept any input of length 1 or greater. 

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

The DFA successfully accepts strings starting with 'a' or 'b' (any non-empty string) and rejects empty strings.

---

## Conclusion

The automaton was successfully designed and simulated. It correctly accepts the specified valid strings and rejects all invalid strings, demonstrating the practical implementation of automata using simulation software.

---

## Output

![Output](EXP%2022%20-%20Output.png)
