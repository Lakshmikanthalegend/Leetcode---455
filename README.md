# Leetcode-455
The problem is solved using a greedy algorithm. First, sort the greed factors (g) and cookie sizes (s) in ascending order to facilitate efficient assignment. Then, use two pointers: one iterating over children (g) and the other over cookies (s). Assign the smallest available cookie that satisfies the current child's greed. If a cookie is too small, move to the next cookie. Continue until all children or cookies are processed. This ensures maximum content children by always satisfying the least greedy child first, minimizing unused resources.
