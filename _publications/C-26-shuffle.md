---
title: "Decomposing regular languages under shuffle along trajectories"
collection: publications
date: 2026-07-02
type: conference
venue: "CIAA'26"
year: 2026
bookfullname: "Proceedings of the 30th International Conference on Implementation and Application of Automata"
coauthors: "Sungmin Kim, Hyunki Hong, Taeryung Lim, Yo-Sub Han and Kai Salomaa"
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
<strong>Shuffle along trajectories:</strong> 
the shuffle of two languages $L_1$ and $L_2$ over $\Sigma$
along a trajectory language $T$ over {$0,1$}
is the language obtained by interleaving strings $w_1\in L_1$ and $w_2\in L_2$
by placing characters from $w_1$ and $w_2$
respectively at positions designated by $0$'s and $1$'s
in trajectories $t\in T$.
<br>
<strong>Decomposition under shuffle along trajectories:</strong>
given a regular language $R$ and a trajectory language $T$,
compute two languages $L_1$ and $L_2$ whose shuffle along $T$
equals $R$.

## Summary of results
<ul>
<li> Algorithms for computing the decompositions for two well-known trajectory languages:
    <ul>
        <li> $(01)^*+(10)^*$ (perfect shuffle) </li>
        <li> $(01)^*(\lambda+0+00)$ (2-comet shuffle) </li>
    </ul>
</li>
<li> A decomposition technique using Büchi automata, where the language of the automaton is non-empty iff there exists a non-trivial decomposition of $R$ </li>
<li> Corollary: with respect to either trajectory, if there exists a non-trivial decomposition of $R$, then there exists a decomposition where both languages are regular. </li>
</ul>

<br>
<small>
<strong>Keywords</strong>
shuffle along trajectories, language decomposition, Büchi automata, control string
</small>
