---
title: "Pattern matching under &#x211B;-congruence"
collection: publications
date: 2026-07-02
type: conference
venue: "CIAA'26"
year: 2026
bookfullname: "Proceedings of the 30th International Conference on Implementation and Application of Automata"
coauthors: "Sungmin Kim, Hyundong Jin and Yo-Sub Han"
selected: false
toappear: true
pages: 
volume: 
month: August
paperurl: 
slidesurl:
codeurl:
---

## Definitions
<strong>$\mathcal{R}$-congruence:</strong> For an integer $k$,
two strings $w_1$ and $w_2$ are $\sim_k^{\mathcal{R}}$-congruent ($w_1\sim_k^{\mathcal{R}} w_2$)
if each prefix of $w_1$ and $w_2$
satisfies Simon's congruence to some prefix of $w_2$ and $w_1$, respectively.
The family of $\mathcal{R}$-congruence closures
are exactly the languages whose syntactic monoid is $\mathcal{R}$-trivial (Brzozowski and Fich, 1980). <br>
<strong>Pattern matching under $\mathcal{R}$-congruence:</strong>
find all substrings of a text $\texttt{T}$ that matches a pattern $\texttt{P}$
(i.e., $\sim_k^{\mathcal{R}}$-congruent to $\texttt{P}$).

## Summary of results
<ul>
<li> A $O(|w|+|v|)$ time algorithm that decides $w\sim_k^{\mathcal{R}}v$ </li>
<li> A $O(|\Sigma||\texttt{P}|+|\Sigma||\texttt{T}|k)$ time algorithm
for the pattern matching under $\mathcal{R}$-congruence problem
when $k$ is given </li>
<li> A $O(|\texttt{T}||\texttt{P}|)$ time algorithm
for the pattern matching under $\mathcal{R}$-congruence problem
for all $k\le |\texttt{T}|$ </li>
</ul>

<br>
<small>
<strong>Keywords</strong>
$\mathcal{R}$-congruence, Simon's congruence, pattern matching, subsequences
</small>
