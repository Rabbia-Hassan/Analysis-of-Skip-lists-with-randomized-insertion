# Analysis-of-Skip-lists-with-randomized-insertion
Analysis of Skip-lists with randomized insertion
# Question
We are supposed to prove that each successive level of Skip-lists contains elements which follows a probability distribution of coin with successive heads.
# Steps
1. Create a skip-lists (say S) data structure with randomized head/tail scenario.
2. Assume a relatively large number of elements in some lists (say L) to be inserted in the skip-list. On random, pick a single element x from L and insert it into S and then decide at which level(s) the x is supposed to be inserted.
3. After each insertion, store the number of elements in each levels of S. As the number of elements grow you will have prove/disprove that the number of elements follow a distribution or not.
4. Repeat the process at-last 3 times and log every step.
5. Plot the logged data in the form of figures.
