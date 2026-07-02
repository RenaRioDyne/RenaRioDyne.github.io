---
title: "On Simon's congruence closure of a string"
collection: publications
date: 2023-09-13
type: journal
venue: "TCS"
year: 2023
bookfullname: "Theoretical Computer Science"
coauthors: "Sungmin Kim, Yo-Sub Han, Sang-Ki Ko and Kai Salomaa"
selected: false
toappear: false
pages: "p. 114078"
volume: 972
month: September
paperurl: "https://doi.org/10.1016/j.tcs.2023.114078"
slidesurl:
codeurl:
---

## Definitions
<strong>Simon's congruence:</strong> For an integer $k$,
two strings $w_1$ and $w_2$ are $k$-congruent ($w_1\sim_k w_2$)
if they have the same set of subsequences
of at most $k$.<br>
<strong>Simon's congruence closure:</strong>
$\texttt{Closure}_k(w)$ consists of the strings
that are $k$-congruent to $w$.

## Summary of results
<ul>
<li> Two DFA constructions for $\texttt{Closure}_k(w)$ </li>
<li> A lower bound for the number of states in a DFA for $\texttt{Closure}_k(w)$ </li>
<li> A polynomial-time algorithm for the following problem: given a string $w$ and a context-free language $L$ over a fixed-sized alphabet, decide whether or not there exists a string in $L$ that is $k$-congruent to $w$ </li>
<li> An NP-completeness proof for the same problem over variable-sized alphabets </li>
</ul>

<br>
<small>
<strong>Keywords</strong>
Simon's congruence, state complexity, finite automata, shortlex normal forms
</small>

[link to conference version](/publications/C-23-closure)