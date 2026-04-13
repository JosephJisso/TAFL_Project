# NFA to DFA Converter

An interactive web app for Theory of Automata and Formal Languages that converts an NFA into an equivalent DFA using subset construction.

## About

This project is a single page application built with plain HTML, CSS, and JavaScript.
It combines concept explanation and practical conversion in one interface.

## Features

1. Editable NFA definition with states, alphabet, start state, and accept states
2. Dynamic transition table builder
3. Preset examples for quick demonstrations
4. Automatic NFA to DFA conversion by subset construction
5. NFA and DFA graph visualization
6. Detailed conversion steps view
7. DFA transition table output
8. Epsilon closure panel for epsilon transitions
9. String testing with full run and step mode
10. DFA minimization with partition refinement
11. SVG export and table copy actions
12. Theme toggle and cinematic visual presentation

## Tech Stack

1. HTML
2. CSS
3. Vanilla JavaScript

No build setup is required.

## Run on Localhost

1. Open a terminal in the project folder
2. Start Python and run these lines

python
from http.server import test
test(port=8000)

3. Open this URL in your browser

http://localhost:8000/nfa_to_dfa.html

## How to Use

1. Set states, alphabet, start state, and accept states
2. Build the transition table
3. Fill transitions using comma separated state names or the empty symbol
4. Click CONVERT
5. Review results in these tabs: NFA GRAPH, STEPS, DFA GRAPH, TABLE, TEST, epsilon CLOSURE, MINIMIZE

## Input Notes

1. Use comma separated names for lists of states
2. Include epsilon in the alphabet only when epsilon transitions are needed
3. Ensure accept states are valid members of the state set

## Keyboard Shortcuts

1. Enter or r runs conversion
2. Keys 1 through 7 switch tabs

## Author

Joseph Jisso Aliyath
