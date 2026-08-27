# Experiment 21: Design and Simulation of a Deterministic Finite Automaton (DFA) Using Simulator

## Aim

To design and simulate a Deterministic Finite Automaton (DFA) using a simulator to accept the string having ‘ab’ as substring over the set {a,b}.

---

## Problem Statement

Design a DFA for the language of strings over {a, b} containing 'ab' as substring.

---

## Theory

A DFA can track the occurrence of a substring. It starts in an initial state, transitions through intermediate states as prefixes of the substring are read, and reaches an accepting state when the full substring is encountered. Once in the accepting state, it remains there for any subsequent input.

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

The DFA successfully accepts strings with 'ab' as a substring and rejects others.

---

## Conclusion

The automaton was successfully designed and simulated. It correctly accepts the specified valid strings and rejects all invalid strings, demonstrating the practical implementation of automata using simulation software.

---

## Output

![Output](EXP%2021%20-%20Output.png)
