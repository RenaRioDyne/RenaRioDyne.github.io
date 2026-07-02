---
title: "Matching patterns with variables under Simon’s congruence"
collection: publications
date: 2023-10-05
type: conference
venue: "RP'23"
year: 2023
bookfullname: "Proceedings of the 17th International Conference on Reachability Problems"
coauthors: "Pamela Fleischmann, Sungmin Kim, Tore Koß, Florin Manea, Dirk Nowotka, Stefan Siemer and Max Wiedenhöft"
selected: false
toappear: false
pages: "pp. 155--170"
volume: 
month: October
paperurl: "https://link.springer.com/chapter/10.1007/978-3-031-45286-4_12"
slidesurl:
codeurl:
---

## Definitions
<strong>Simon's congruence:</strong> For an integer $k$,
two strings $w_1$ and $w_2$ are $k$-congruent ($w_1\sim_k w_2$)
if they have the same set of subsequences
of at most $k$.<br>
<strong>Matching patterns with variables problem
under Simon's congruence:</strong>
given a pattern $\alpha$ over the set of variables and terminals
and a string $w$ over the set of terminals,
find a substitution $h$
that satisfies $h(\alpha)\sim_k w$.

## Summary of results
<ul>
<li> NP-completeness proofs for the following problems:
    <ul>
        <li> matching patterns with variables under Simon's congruence when the pattern is $k$-universal (i.e., contains all subsequences of length at most $k$) </li>
        <li> matching patterns with variables under Simon's congruence against general patterns </li>
        <li> word equation problems under Simon's congruence (i.e., when $w$ also contains variables and the substitution should satisfy $h(\alpha)\sim_k h(w)$)
        when $k\le |\alpha|+|w|$</li>
    </ul>
</li>
<li> Membership in P for matching patterns with variables against regular patterns (i.e., each variable occurs at most once) </li>
</ul>

<br>
<small>
<strong>Keywords</strong>
Simon's congruence, matching patterns with variables, word equation, string solving
</small>

[link to journal version](/publications/J-26-variables)