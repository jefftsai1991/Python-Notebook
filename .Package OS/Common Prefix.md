# [14. Longest Common Prefix](https://leetcode.com/problems/longest-common-prefix/description/)


Write a function to find the longest common prefix string amongst an array of strings.  
If there is no common prefix, return an empty string `""`.

Example 1:
```
Input: ["flower","flow","flight"]
Output: "fl"
```
Example 2:
```
Input: ["dog","racecar","car"]
Output: ""
Explanation: There is no common prefix among the input strings.
```
Code in Python 3
```python
class Solution:
    def longestCommonPrefix(self, strs):
        import os 
        return os.path.commonprefix(strs)
```

