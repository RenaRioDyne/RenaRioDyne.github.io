---
title: "[Journal] Approximate Cartesian Tree Pattern Matching"
collection: publications
permalink: /publications/jour3
excerpt: "Matching Cartesian trees in the approximate setting, using the edit-distance approach. In computing the edit distance, we achieve a linear speedup compared to the conference version of the paper. The speedup is based on the fast computation of the max-min convolution between two monotonic arrays."
date: 2025-08-04
venue: "Theoretical Computer Science (to appear)"
classes: wide
---
## Summary
Read the abstract.

## Contribution
Matching Cartesian trees in the approximate setting, using the edit-distance approach. In computing the edit distance, we achieve a linear speedup compared to the conference version of the paper. The speedup is based on the fast computation of the max-min convolution between two monotonic arrays.

## Abstract
The Cartesian tree of a string is a binary tree, which is useful in capturing minimalities within strings. We study the approximate pattern matching problem for two Cartesian trees of two strings. We design a polynomial-time algorithm that computes the minimum edit cost when a given string is edited to match the Cartesian tree of the other string. We also design a linear-time algorithm that computes the (max,min)-convolution between two sorted arrays, which we use to speed up the algorithm computing the edit cost. Then, we adapt the algorithm that computes the edit cost to the approximate pattern matching problem, where we find all substrings of a given text that match a given Cartesian tree pattern within a given number of edit operations. We also consider variant problems such as the approximate Cartesian matching under Hamming distance, and present polynomial-time algorithms for the considered problems.

## Recommended citation:
Sungmin Kim and Yo-Sub Han. "Approximate Cartesian tree pattern matching." Theoretical Computer Science (TCS), 2025, To appear.
