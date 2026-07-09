---
title: "Pattern mining under Simon's congruence"
collection: publications
date: 2026-07-09
type: journal
venue: "I&C"
year: 2026
bookfullname: "Information and Computation"
coauthors: "Sungmin Kim and Yo-Sub Han"
selected: true
toappear: true
pages: 
volume: 
month: 
paperurl: 
slidesurl:
codeurl:
---


## Definitions
<strong>Simon's congruence:</strong> For an integer $k$,
two strings $w_1$ and $w_2$ are $k$-congruent ($w_1\sim_k w_2$)
if they have the same set of subsequences
of at most $k$.
A substring of a text $\texttt{T}$ matches a pattern $\texttt{P}$
if it is $k$-congruent to $\texttt{P}$.<br>
<strong>Complete pattern mining problem under Simon's congruence:</strong>
compute patterns $\texttt{P}_k$
for each $k\le |\texttt{T}|$
that maximizes the number of matches with respect to each $k$.

## Summary of results
<ul>
<li> A $O(|\Sigma||\texttt{T}|^2\log^2|\texttt{T}|)$ time algorithm for the complete pattern mining problem under Simon's congruence </li>
<li> A tree data structure constructable in the same time bound that captures the maximum $k$ allowing congruence between pairs of substrings of a text </li>
</ul>

<br>
<small>
<strong>Keywords</strong>
Simon's congruence, pattern mining, string algorithm, data structure, lowest common ancestor
</small>

[link to conference version](/publications/C-25-mining)