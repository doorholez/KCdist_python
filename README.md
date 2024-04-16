# KCdist_python
calculate Kendall-Colijn distance in python\
i find there is only R version so i write it :)

usage:
```
import KC_dist
newick_str1 = '...'
newick_str2 = '...'
dist = KC_dist.KC_dist(newick_str1, newick_str2, lam = 0.5)
# Takes 2 newick strs and a lambda (optional, default is 0), returns the KC dist of 2 trees.
# Requires all tip nodes in 2 trees are identical
```
