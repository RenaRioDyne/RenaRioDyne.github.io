---
title: "Simon's congruence pattern matching"
collection: publications
date: 2024-05-01
type: journal
venue: "TCS"
year: 2024
bookfullname: "Theoretical Computer Science"
coauthors: "Sungmin Kim, Sang-Ki Ko and Yo-Sub Han"
selected: true
toappear: false
pages: "p. 114478"
volume: 994
month: May
paperurl: "https://doi.org/10.1016/j.tcs.2023.114078"
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
        <li> finding the most frequent string among the matches of the pattern </li>
        <li> answering queries for the string with the $g^\text{th}$ largest multiplicity among the matches of the pattern </li>
    </ul>
</li>
</ul>

<br>
<small>
<strong>Keywords</strong>
Simon's congruence, state complexity, finite automata, shortlex normal forms
</small>

[link to conference version](/publications/C-22-matching)