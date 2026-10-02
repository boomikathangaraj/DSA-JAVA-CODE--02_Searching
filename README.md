DSA-JAVA-CODE-02-SEARCHING

Searching

Searching is a fundamental operation in data structures used to locate a required element within a collection of data. The efficiency of searching depends on the organization of the data and the technique used.

This repository contains Java implementations of searching problems using a sorted array and the Binary Search approach.

Searching Programs

Searching
│
├── 01. Binary Search
│
└── 02. Search Insert Position

01. Binary Search

Theory:
Binary Search is a searching algorithm used to find a target element in a sorted array. It works by repeatedly reducing the search range by half instead of checking every element sequentially.

Working:
The search begins with two boundaries, "left" and "right". The middle element is calculated and compared with the target.

- If the middle element is equal to the target, the search is successful.
- If the target is greater than the middle element, the search continues in the right half.
- If the target is smaller than the middle element, the search continues in the left half.

The process continues until the target is found or the search range becomes empty.

Key Idea:
At every step, one half of the remaining search space is eliminated.

Time Complexity: "O(log n)"
Space Complexity: "O(1)"

---

02. Search Insert Position

Theory:
Search Insert Position is a Binary Search problem in which the objective is to determine the correct position of a target value in a sorted array. If the target already exists, its index is returned. Otherwise, the position where it can be inserted while preserving the sorted order is returned.

Working:
The algorithm maintains "left" and "right" boundaries and repeatedly checks the middle element. Based on the comparison with the target, the search range is adjusted. When the search ends, the remaining boundary gives the appropriate insertion position.

Key Idea:
Use the properties of a sorted array to find the target position without checking every element.

Time Complexity: "O(log n)"
Space Complexity: "O(1)"
