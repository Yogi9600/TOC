# Experiment 33: Design and Simulation of a Nondeterministic Finite Automaton (NFA) Using Simulator

## Aim

To design and simulate a Nondeterministic Finite Automaton (NFA) using simulator to accept the string the start with a and end with b over set {a,b} and check W= abaab is accepted or not.

---

## Problem Statement

Design an NFA for the language of strings over {a, b} that start with 'a' and end with 'b'. Check if "abaab" is accepted.

---

## Theory

An NFA can use non-determinism to guess when the string is ending. It starts with an 'a', loops on 'a' or 'b' in an intermediate state, and transitions to an accepting state upon reading a 'b' that it guesses is the final character.

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
7. Test the automaton using different input strings (including "abaab").
8. Verify whether the strings are accepted or rejected.

---

## Result

The NFA successfully accepts strings starting with 'a' and ending with 'b'. The string "abaab" is accepted.

---

## Conclusion

The automaton was successfully designed and simulated. It correctly accepts the specified valid strings and rejects all invalid strings, demonstrating the practical implementation of automata using simulation software.

---

## Output

![Output](EXP%2033%20-%20Output.png)
