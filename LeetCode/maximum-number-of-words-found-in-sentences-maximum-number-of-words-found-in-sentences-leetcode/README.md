# Maximum Number of Words Found in Sentences - LeetCode

## Platform: LeetCode
### Problem Link: [Maximum Number of Words Found in Sentences - LeetCode](https://leetcode.com/problems/maximum-number-of-words-found-in-sentences/submissions/2027646031/?envType=problem-list-v2&envId=dra3cn57)

## Problem Description
A sentence is a list of words that are separated by a single space with no leading or trailing spaces.

You are given an array of strings sentences, where each sentences[i] represents a single sentence.

Return the maximum number of words that appear in a single sentence.

 
Example 1:

Input: sentences = ["alice and bob love leetcode", "i think so too", "this is great thanks very much"]
Output: 6
Explanation: 
- The first sentence, "alice and bob love leetcode", has 5 words in total.
- The second sentence, "i think so too", has 4 words in total.
- The third sentence, "this is great thanks very much", has 6 words in total.
Thus, the maximum number of words in a single sentence comes from the third sentence, which has 6 words.


Example 2:

Input: sentences = ["please wait", "continue to fight", "continue to win"]
Output: 3
Explanation: It is possible that multiple sentences contain the same number of words. 
In this example, the second and third sentences (underlined) have the same number of words.


 
Constraints:


	1 <= sentences.length <= 100
	1 <= sentences[i].length <= 100
	sentences[i] consists only of lowercase English letters and ' ' only.
	sentences[i] does not have leading or trailing spaces.
	All the words in sentences[i] are separated by a single space.



## Constraints

	1 <= sentences.length <= 100
	1 <= sentences[i].length <= 100
	sentences[i] consists only of lowercase English letters and ' ' only.
	sentences[i] does not have leading or trailing spaces.
	All the words in sentences[i] are separated by a single space.



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
Array, String

---

## Solution Code

```c++
}
            }
                    words++;
            for (char ch : s) {
                if (ch == ' ') {
            int words = 1;  

        for (string s : sentences) {
        int maxWords = 0;

class Solution {
public:
    int mostWordsFound(vector<string>& sentences) {
```
