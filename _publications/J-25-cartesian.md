---
title: "Approximate Cartesian tree pattern matching"
collection: publications
date: 2025-11-21
type: journal
venue: "TCS"
year: 2025
bookfullname: "Theoretical Computer Science"
coauthors: "Sungmin Kim and Yo-Sub Han"
selected: true
toappear: false
pages: "p. 115506"
volume: 1056
month: November
paperurl: "https://doi.org/10.1016/j.tcs.2025.115506"
slidesurl:
codeurl:
---

## Definitions
<strong>Cartesian tree:</strong>
for a string over integer characters, 
if the string is of length 0, it is the empty tree.
Otherwise, take the minimum integer as the root, and recursively build
the left and right subtrees using the prefix and suffix split by the minimum integer.<br>
<strong>Approximate pattern matching under Cartesian tree equivalence:</strong>
find all substrings of a given text
that can be transformed into another string
with the same Cartesian tree as the given pattern
by applying at most a given number of edits.

## Summary of results
<ul>
<li> A $O(|w|^3|u|(|w|+|u|))$ time algorithm for computing the edit distance
from $w$ to $u$ </li>
<li> A $O(|\texttt{T}|^3|\texttt{P}|t)$ time algorithm for
the approximate pattern matching problem under Cartesian tree equivalence,
where $t$ is the maximum number of edits </li>
<li> A $O(|\texttt{T}||\texttt{P}|t)$ time algorithm for
the approximate pattern matching problem under Cartesian tree equivalence
when only substitutions are allowed </li>
<li> An algorithm that computes the max-min convolution between two non-decreasing sequence of integers of length $m$ and $n$ in $O(m+n)$ time </li>
</ul>

<br>
<small>
<strong>Keywords</strong>
Cartesian tree, approximate pattern matching, dynamic programming, recurrence relation, max-min convolution
</small>

[link to conference version](/publications/C-24-cartesian)