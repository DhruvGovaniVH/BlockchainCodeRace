# Code Race

#### Rules :
1. You **can't** use **Chat GPT** or any other **AI Tools** to write the program.
2. You **can't** search on **Google** also as This Programs can be written using the basic programming concepts taught in college.
3. You can use any **Programming** language.
---
### 1. Roman to Integer

Participants : Tushar, Parth, Utkarsh, Manali, Kiran, Vivek, Paramanad
---
Roman numerals are represented by seven different symbols: I, V, X, L, C, D and M.

**Symbol ----> Value**

I ----> 1

V ----> 5

X ----> 10

L ----> 50

C ----> 100

D ----> 500

M ----> 1000

For example, 2 is written as II in Roman numeral, just two ones added together. 12 is written as XII, which is simply X + II. The number 27 is written as XXVII, which is XX + V + II.

Roman numerals are usually written largest to smallest from left to right. However, the numeral for four is not IIII. Instead, the number four is written as IV. Because the one is before the five we subtract it making four. The same principle applies to the number nine, which is written as IX. There are six instances where subtraction is used:

* I can be placed before V (5) and X (10) to make 4 and 9. 
* X can be placed before L (50) and C (100) to make 40 and 90. 
* C can be placed before D (500) and M (1000) to make 400 and 900.
Given a roman numeral, convert it to an integer.
 
**Example 1:**
Input: s = "III"
Output: 3
Explanation: III = 3.

**Example 2:**
Input: s = "LVIII"
Output: 58
Explanation: L = 50, V= 5, III = 3.

**Example 3:**
Input: s = "MCMXCIV"
Output: 1994
Explanation: M = 1000, CM = 900, XC = 90 and IV = 4.
 
**Constraints:**
* 1 <= s.length <= 15
* s contains only the characters ('I', 'V', 'X', 'L', 'C', 'D', 'M').
* It is guaranteed that s is a valid roman numeral in the range [1, 3999].

**Create Function as below:**
```
class Solution {
    func romanToInt(_ s: String) -> Int {
    }
}
```
---
### 2. Two Sum

Participants : Nisarg, Parita, Pragati, Mayuri, Ankit, Rishabh
---
Given an array of integers  `nums` and an integer  `target`, return  _indices of the two numbers such that they add up to  `target`_.

You may assume that each input would have  **_exactly_  one solution**, and you may not use the  _same_  element twice.

You can return the answer in any order.

**Example 1:**

**Input:** nums = [2,7,11,15], target = 9
**Output:** [0,1]
**Explanation:** Because nums[0] + nums[1] == 9, we return [0, 1].

**Example 2:**

**Input:** nums = [3,2,4], target = 6
**Output:** [1,2]

**Example 3:**

**Input:** nums = [3,3], target = 6
**Output:** [0,1]

**Constraints:**

-   `2 <= nums.length <= 104`
-   `-109 <= nums[i] <= 109`
-   `-109 <= target <= 109`
-   **Only one valid answer exists.**

**Create Function as below:**

```
func  twoSum(_  nums: [Int], _  target: Int) -> [Int] {
}
```
