# 🧮 4Sum — LeetCode Problem #18

Solve the classic 4Sum problem using sorting and two-pointer technique.

🔗 [Problem Link](https://leetcode.com/problems/4sum/submissions/1735495069/)

---

## 🧠 Problem Statement

Given an array `nums` of integers and an integer `target`, return all **unique quadruplets** `[a, b, c, d]` such that:

- `nums[a] + nums[b] + nums[c] + nums[d] == target`
- All indices are distinct
- You may return the answer in any order

---

## ✅ Approach

- Sort the array
- Fix two pointers `i` and `j`
- Use two-pointer scan (`left`, `right`) to find valid quadruplets
- Skip duplicates to ensure uniqueness

---

 ## 📊 Complexity

```text
Time Complexity: O(n³)
- Outer two loops: O(n²)
- Inner two-pointer scan: O(n)

Space Complexity: O(k)
- Where k = number of valid quadruplets stored in result

```
## 🧪 Example Test Cases

```python
Input: nums = [1,0,-1,0,-2,2], target = 0
Output: [[-2,-1,1,2],[-2,0,0,2],[-1,0,0,1]]

Input: nums = [2,2,2,2,2], target = 8
Output: [[2,2,2,2]]
