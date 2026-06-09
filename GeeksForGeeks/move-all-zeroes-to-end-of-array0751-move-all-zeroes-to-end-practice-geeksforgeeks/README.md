# Move All Zeroes to End | Practice | GeeksforGeeks

<div align="center">

![LeetCode](https://img.shields.io/badge/Platform-GeeksForGeeks-blue?style=for-the-badge&logo=leetcode)
![Difficulty](https://img.shields.io/badge/Difficulty-Medium-yellow?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Solved-success?style=for-the-badge)

**Submitted:** 6/9/2026, 10:22:10 PM

[🔗 View on GeeksForGeeks](https://www.geeksforgeeks.org/batch/gfg-160-problems/track/arrays-gfg-160/problem/move-all-zeroes-to-end-of-array0751)

</div>

---

## 📋 Problem Description

> Problem statement not captured. Please refer to the link above.

---

## 📝 Constraints

> Constraints not captured. Please check the problem link.

---

## 💡 Examples

> Examples not captured. Please check the problem link.

---

## 🧠 Solution Approach

### Algorithm
> Double pointer, greedy, or hashing-based approach depending on the optimal problem requirements. Elements are processed linearly or sorted first to reduce search time.

### Key Observations
- Optimal solutions typically avoid nested loops by using auxiliary data structures like sets, maps, or arrays.
- Consider boundary cases such as empty inputs, negative numbers, or extremely large array sizes.

### Related Concepts
```
Data Structures, Problem Solving
```

---

## ⏱️ Complexity Analysis

| Metric | Complexity | Details |
|--------|-----------|---------|
| **Time** | O(N) in the average/worst-case scenario where N is the size of the input. | Efficient iteration through data |
| **Space** | O(1) auxiliary space, or O(N) if utilizing hash tables or lists for storage. | Minimal extra space required |

---

## 💻 Solution Code

```sort by
class Solution {
  public:
    void pushZerosToEnd(vector<int>& arr) {
        // code here
        int low = 0 ; 
        for(int i = 0 ; i<arr.size() ; i++){
            if(arr[i] != 0 ){
                swap(arr[low] , arr[i]); 
                low++;
            }
        }
        
        
    }
};
```

---

<div align="center">

**Created with ❤️ by DSA Sync**

</div>
