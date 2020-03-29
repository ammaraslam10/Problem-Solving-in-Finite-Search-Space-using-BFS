# Problem-Solving-in-Finite-Search-Space-using-BFS

This is a simple BFS algortihm that will solve problems by searching finite search space

It is written in JavaScript and uses ProcessingJs to visualise the tree.
Tested on Chrome 80.0.3987.149 only.

Input file format:
Input file comprises of header, state descriptions, rule descriptions and transition matrix. First line of the
file is header; it is a space separated triplet of integers (M N T). M represents number of states, N represents
number of rules and T represents number of test cases. Header is followed by an empty line. Description of
all possible states follows header (after empty line). Each line comprises of one state description. State
descriptions follow an empty line. State descriptions are followed by rule descriptions (after empty line).
An M x N transition matrix of integers follows rule descriptions (after empty line) which describe transition
of each state after applying each action. Transition matrix is followed by an empty line which is followed
by T number of test cases. Each test case is represented in a line. Each line is a pair of strings separated by
tab, first string is a state representing initial state and second string is also a state representing final state.

The script will print results on console and it will display them on screen as well, There's a checkbox to enable/disable the visualization. 
