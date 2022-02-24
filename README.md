# Finite-Automata
C++ program that will simulate a deterministic finite automata processes an input string


## Definition
A **finite automaton** is a 5-tuple (Q, A, *f*, q, F) where

1. Q is a finite set called **states**
2. A is a finite set called **alphabet**
3. *f*: Q X A -> Q is the **transition function**
4. q, an element of Q is the **start state**
5. F, a proper subset of Q, is the **set of accept states**

## Project ##
The user will be able to input a deterministic finite automata (DFA) by specifiing the set of states, alphabet, transition function, thee start state, and set of acceept states.

The user will then be able to input a string with characters of the specified alphabet. The program will run the string in the DFA and return if the DFA accepts the string.