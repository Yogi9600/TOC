# Experiment 32: Design and Simulation of a Deterministic Finite Automaton (DFA) Using Simulator

## Aim

To design and simulate a Deterministic Finite Automaton (DFA) using a simulator to accept strings in which a’s always appear tripled over input {a,b}.

---

## Problem Statement

Design a DFA for the language of strings over {a, b} where every 'a' is part of a sequence of exactly three 'a's (or a multiple of three).

---

## Theory

A DFA can enforce patterns by requiring specific sequences of transitions. To ensure 'a's appear tripled, reading an 'a' must force the reading of two more 'a's before any 'b' can be accepted. The state after reading three 'a's (or after reading 'b's) is the accepting state.

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

The DFA successfully accepts strings where 'a's appear in multiples of three.

---

## Conclusion

The automaton was successfully designed and simulated. It correctly accepts the specified valid strings and rejects all invalid strings, demonstrating the practical implementation of automata using simulation software.

---

## Output

![Output](EXP%2032%20-%20Output.png)
