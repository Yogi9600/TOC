# Experiment 34: Design and Simulation of a Nondeterministic Finite Automaton (NFA) Using Simulator

## Aim

To design and simulate a Nondeterministic Finite Automaton (NFA) using simulator to accept the string that start and end with different symbols over the input {a,b}.

---

## Problem Statement

Design an NFA for the language of strings over {a, b} that start with 'a' and end with 'b', or start with 'b' and end with 'a'.

---

## Theory

An NFA can use an epsilon transition or multiple starting paths to handle two possible starting conditions. One path handles starting with 'a' and ending with 'b', while the other handles starting with 'b' and ending with 'a'.

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

The NFA successfully accepts strings that start and end with different symbols.

---

## Conclusion

The automaton was successfully designed and simulated. It correctly accepts the specified valid strings and rejects all invalid strings, demonstrating the practical implementation of automata using simulation software.

---

## Output

![Output](EXP%2034%20-%20Output.png)
