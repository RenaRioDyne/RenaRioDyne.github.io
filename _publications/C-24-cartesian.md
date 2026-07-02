---
title: "Approximate Cartesian tree pattern matching"
collection: publications
date: 2024-07-27
type: conference
venue: "DLT'24"
year: 2024
bookfullname: "Proceedings of the 28th International Conference on Developments in Language Theory"
coauthors: "Sungmin Kim and Yo-Sub Han"
selected: false
toappear: false
pages: "pp. 189--202"
volume: 
month: July
paperurl: "https://link.springer.com/chapter/10.1007/978-3-031-66159-4_14"
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
<li> A $O(|w|^3|u|(|w|+|u|)^2)$ time algorithm for computing the edit distance
from $w$ to $u$ </li>
<li> A $O(|\texttt{T}|^3|\texttt{P}|t^2)$ time algorithm for
the approximate pattern matching problem under Cartesian tree equivalence,
where $t$ is the maximum number of edits </li>
<li> A $O(|\texttt{T}||\texttt{P}|t^2)$ time algorithm for
the approximate pattern matching problem under Cartesian tree equivalence
when only substitutions are allowed </li>
</ul>
Note: improved algorithms are given in the journal version of the paper.

<br>
<small>
<strong>Keywords</strong>
Cartesian tree, approximate pattern matching, dynamic programming, recurrence relation
</small>

[link to journal version](/publications/J-25-cartesian)