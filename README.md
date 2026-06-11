# LeetCode Solutions Repository

This repository contains my solutions to LeetCode problems implemented in various programming languages. The purpose of this repository is to strengthen problem-solving skills, improve algorithmic thinking, and prepare for coding interviews and competitive programming contests.

## 🎯 Goals

- Practice Data Structures and Algorithms (DSA)
- Improve problem-solving speed and accuracy
- Track coding progress consistently
- Prepare for technical interviews
- Build a strong understanding of algorithmic patterns

## 📚 Topics Covered

- Arrays
- Strings
- Linked Lists
- Stacks
- Queues
- Hash Tables
- Trees
- Binary Search Trees
- Heaps / Priority Queues
- Graphs
- Recursion
- Backtracking
- Dynamic Programming
- Greedy Algorithms
- Sliding Window
- Two Pointers
- Binary Search
- Bit Manipulation
- Sorting and Searching

## 📂 Repository Structure

```
LeetCode/
│
├── Arrays/
├── Strings/
├── LinkedLists/
├── Stack/
├── Queue/
├── Trees/
├── Graphs/
├── DynamicProgramming/
├── Greedy/
├── BinarySearch/
└── Miscellaneous/
```

Each solution includes:

- Problem name
- Problem number
- Solution code
- Time complexity
- Space complexity
- Explanation (where applicable)

## 🛠 Languages Used

- Python
- JavaScript
- C++
- Java

## 📈 Progress

| Difficulty | Solved |
|------------|---------|
| Easy | 0 |
| Medium | 0 |
| Hard | 0 |
| Total | 0 |

> Update the table as you solve more problems.

## 🚀 Example Solution Format

### 1. Two Sum

**Difficulty:** Easy

**Approach:** Hash Map

**Time Complexity:** O(n)

**Space Complexity:** O(n)

```python
def twoSum(nums, target):
    seen = {}

    for i, num in enumerate(nums):
        complement = target - num

        if complement in seen:
            return [seen[complement], i]

        seen[num] = i
```

## 💡 Why This Repository?

Consistent practice is one of the best ways to master Data Structures and Algorithms. This repository serves as a personal learning journal and a reference for revisiting solved problems and common patterns.

## 📌 Resources

- LeetCode: https://leetcode.com/
- NeetCode: https://neetcode.io/
- GeeksforGeeks: https://www.geeksforgeeks.org/

## 🤝 Contributions

Suggestions, optimizations, and alternative approaches are always welcome.

## ⭐ Support

If you find this repository useful, consider giving it a star.

## 👨‍💻 Author

**Abdurahman Siraj**

*"Solve problems daily. Consistency beats intensity."*
