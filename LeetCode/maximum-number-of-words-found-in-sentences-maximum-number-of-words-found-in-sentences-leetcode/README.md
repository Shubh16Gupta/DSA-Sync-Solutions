# Maximum Number of Words Found in Sentences - LeetCode

## Platform: LeetCode
### Problem Link: [Maximum Number of Words Found in Sentences - LeetCode](https://leetcode.com/problems/maximum-number-of-words-found-in-sentences/submissions/2027646031/?envType=problem-list-v2&envId=dra3cn57)

## Problem Description
No description provided.

## Constraints
No constraints provided.

## Examples
No examples provided.

---

## AI Generated Notes

### Approach
Double pointer, greedy, or hashing-based approach depending on the optimal problem requirements. Elements are processed linearly or sorted first to reduce search time.

### Key Observations
- Optimal solutions typically avoid nested loops by using auxiliary data structures like sets, maps, or arrays.
- Consider boundary cases such as empty inputs, negative numbers, or extremely large array sizes.

### Complexity Analysis
- **Time Complexity:** O(N) in the average/worst-case scenario where N is the size of the input.
- **Space Complexity:** O(1) auxiliary space, or O(N) if utilizing hash tables or lists for storage.

### Key Concepts
Data Structures, Problem Solving

---

## Solution Code

```c++
class Solution {
public:
    int mostWordsFound(vector<string>& sentences) {
        int maxWords = 0;

        for (string s : sentences) {
            int words = 1;  

            for (char ch : s) {
                if (ch == ' ') {
                    words++;
                }
            }
```
