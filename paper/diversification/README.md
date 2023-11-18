# ChronoCiphers
This is a guideline on paper's results

## Diversification
- qin-diversifying-top-k-results: definition for traditional diversification
    - Their problem is totally different one from mcgregor one, so they are considering the score and the similarity at the same time, while mcgregor only care about the diversity. Also, fo rthis problme could be changed to an independent set problem, which is NP-hard.
- ravi-heuristic-dispersion-problems
    - Max-Min and Max-Avg
    - 2-approx for max-min, 4-approx for max-avg(under triangle inequality)
    - less than two is NP-hard, negative result
    - polynomial time alg for 1-dimensional max-avg dispersion problem, and an asymptotic pi/2-approx heuristic for 2-dimensional max-avg
- wang-two-geometric-location: (everything in this paper is m=1)
    - gives the dp algorithm for the Eclidean spece m=1, dimension=1, some others even with dimension = 2 is NP-hard.
    - two kinds of definitions for diversification:
        - largest subset that the min distance is >= d
        - fixed size of subset that maximize the min distance

## Fair-Diversification
- mcgregor-max-min-metric: gives 2 approx and 6 approx result
- mcgregor- diverse-data-fairness-constraints: gives 5 approx

## Literature Review
- drosou-big-data-diversity
