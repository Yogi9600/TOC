# Experiment 31: Design and Simulation of a Deterministic Finite Automaton (DFA) Using Simulator

## Aim

To design and simulate a Deterministic Finite Automaton (DFA) using a simulator to accept even number of c’s over the set {a,b,c}.

---

## Problem Statement

Design a DFA for the language of strings over {a, b, c} containing an even number of 'c's.

---

## Theory

A DFA can track the parity (even or odd) of a specific character. It uses two states: one for even parity and one for odd parity. Reading a 'c' toggles the state, while reading 'a' or 'b' keeps the state unchanged. The even state is the accepting state.

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

The DFA successfully accepts strings with an even number of 'c's.

---

## Conclusion

The automaton was successfully designed and simulated. It correctly accepts the specified valid strings and rejects all invalid strings, demonstrating the practical implementation of automata using simulation software.

---

## Output

![Output](EXP%2031%20-%20Output.png)
