---
title: "Simon's congruence pattern matching"
collection: publications
date: 2022-12-14
type: conference
venue: "ISAAC'22"
year: 2022
bookfullname: "Proceedings of the 33rd International Symposium on Algorithms and Computation"
coauthors: "Sungmin Kim, Sang-Ki Ko and Yo-Sub Han"
selected: false
toappear: false
pages: "pp. 60:1--60:17"
volume: 
month: December
paperurl: "https://drops.dagstuhl.de/entities/document/10.4230/LIPIcs.ISAAC.2022.60"
slidesurl:
codeurl:
---

## Definitions
<strong>Simon's congruence:</strong> For an integer $k$,
two strings $w_1$ and $w_2$ are $k$-congruent ($w_1\sim_k w_2$)
if they have the same set of subsequences
of at most $k$.<br>
<strong>Pattern matching under Simon's congruence:</strong>
find all substrings of a text $\texttt{T}$ that matches a pattern $\texttt{P}$
(i.e., $k$-congruent to $\texttt{P}$).

## Summary of results
<ul>
<li> A $O(|\texttt{T}||\Sigma|(|\Sigma|^2+k))$ time algorithm for the pattern matching problem under Simon's congruence </li>
<li> Data structures that allow efficiently solving the pattern matching problem </li>
<li> Efficient solutions for the following variant problems:
    <ul>
        <li> finding longest / shortest matches of the text </li>
        <li> finding the shortest subsequence of the text that is $k$-congruent to the pattern </li>
    </ul>
</li>
</ul>

<br>
<small>
<strong>Keywords</strong>
Simon's congruence, pattern matching, string algorithm, data structure
</small>

[link to journal version](/publications/J-24-matching)