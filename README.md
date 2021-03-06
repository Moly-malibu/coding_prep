# coding_prep
A collection of coding interview problems with my solutions. From various sources including Leet-Code, Interview experiences etc. List of questions at the end of this readme file.
#100DaysOfCode

---

Other Resources:

1. TopCoder Blog - GitHub Repositories With Competitive Programming Libraries [[link](https://www.topcoder.com/blog/github-repositories-with-competitive-programming-libraries/)]
2. Problem Solving with Algorithms and Data Structures using Python [[link](http://interactivepython.org/runestone/static/pythonds/index.html)]
3. RosettaCode [[link](https://rosettacode.org/wiki/Category:Programming_Tasks)]
4. Problem Solving with Algorithms and Data Structures using C++ [[link](https://runestone.academy/runestone/static/cppds/index.html)]
5. Algs4cs Princeton [[link](https://algs4.cs.princeton.edu/lectures/)]
6. Union Find - HackerEarth [[link](https://www.hackerearth.com/practice/notes/disjoint-set-union-union-find/)]
7. Teach Yourself CS [[link](http://teachyourselfcs.com)]
8. LeetCode Patterns [[link](https://medium.com/leetcode-patterns)]

---

## Common Patterns

Arrays/Lists/Strings:

- Two pointers (left/right, slow/fast)  
- Ordered Dictionaries in Python (LRU Cache, LFU Cache)
- Zero Sum Clique Reduction (Optimal Account Balancing, Minimum Cash Flow)
- Merge Intervals, Insert Interval (based on Sorting)
- Largest Number (Custom Comparator operator, Python's map function)
- Implement strStr() (Two pointers, Rabin Karp: Rolling Hash)
- Game of Life

Trie / Prefix Search

- Add and Search Word

Stacks & Queues:

- Design Snake Game (Queues)
- Remove K Digits (Stacks and Greedy algorithm)
- Simplify Path (Stacks)
- Decode String
- Moving Average from Data Stream (Queue)

Backtracking:

- Letter Combinations of a Phone Number
- Word Search
- Add and Search Word - Data structure design
- Permutations II
- Palindrome Partitioning
- Restore IP Addresses

Dynamic Programming

- Bomb Enemy
- Coin Change

Greedy Approach

- Wiggle Subsequence
- Remove K Digits

Ad Hoc:

- Fraction to Recurring Decimal
- Integer to English Word
- Spiral Matrix (yield keyword, generator perspective)

Graphs/Trees:

- DFS (Iterative and Recursive) / O(V+E)
    - Clone Graph (recursive)
    - Coin Change
    - Detect Cycle in a directed graph / Course Schedule
    - Distribute Coins in a Binary Tree
    - Pacific Atlantic Water Flow
    - Robot Room Cleaner
- BFS (Iterative and Recursive)
    - Surrounded Regions
    - Word Ladder (Bi-directional BFS)
    - Optimal Account Balancing
    - Clone Graph (iterative)
    - Binary Tree Level Order Traversal
    - Populating Next Right Pointers in Each Node
- Inorder Traversal (Iterative and Recursive)
- Preorder Traversal (Iterative and Recursive)
- Postorder Traversal (Iterative and Recursive)
- Kosaraju's Algorithm for Strongly Connected Components
- Union-Find Algorithm for Cycle Detection in Undirected Graphs
- Cycle detection in directed graphs using Colors / DFS stack
- Bridges in a graph
- Prim's Algorithm, Kruskal Algorithm: Minimum spanning tree
- Dijkstra's Algorithm - Shortest path from origin to every other node in graph / Greedy / O(ELogV) / only non-negative weights
- Bellman Ford Algorithm - Shortest path from origin to every other node in graph / DP / O(VE)
- Topological Sort for a directed graph
    - Alien Dictionary
- Floyd Warshall Algorithm - All pairs shortest path
- Kirchhoff’s Theorem - Calculating number of Spanning trees Of a Graph

Python

- List Comprehensions (Bomb Enemy, Permutations II)
- zip(*(grid)) generator for transpose (Bomb Enemy, Alien Dictionary)
- Iterators / Ordered Dict (LRU Cache)
- Generator objects
- xor (^) (Adding Two Numbers, Fraction Recurring Decimal, Single Number_2)
- heapq package (Employee Free Time, Kth Largest Element)
- bisect package - helps with binary search (Reverse Pairs, Three Sum, Longest Increasing Subsequence, Find First and Last Position of Element in Sorted Array)
- reverse a list a[::-1]
- zip function (Compare Version Numbers)
- @lru_cache in functools (Minimum cost for tickets)

C++

- Shortforms [[link](https://gist.github.com/aroraakshit/e8f9d45862cf85ec7b698a679ea37748)]

---

## List of Questions


1. LeetCode (Medium) - Design Tic Tac Toe [[link](https://leetcode.com/problems/design-tic-tac-toe/)]
2. LeetCode (Medium) - Longest substring without repeating characters [[link](https://leetcode.com/problems/longest-substring-without-repeating-characters/)]
3. Codility (Hard) - Tree Trip [[link](https://app.codility.com/programmers/task/tree_trip/)]
4. LeetCode (Medium) - Add Two Numbers [[link](https://leetcode.com/problems/add-two-numbers/)]
5. LeetCode (Hard) - Median of Two Sorted Arrays [[link](https://leetcode.com/problems/median-of-two-sorted-arrays/)]
6. LeetCode (Medium) - Three Sum [[link](https://leetcode.com/problems/3sum)]   
7. LeetCode(Medium) - Set Matrix Zeroes [[link](https://leetcode.com/problems/set-matrix-zeroes/)]
8. LeetCode (Medium) - Group Anagrams [[link](https://leetcode.com/problems/group-anagrams/)]
9. LeetCode (Medium) - Longest Palindromic Substring [[link](https://leetcode.com/problems/longest-palindromic-substring/)] ([Manacher's Algorithm](https://www.geeksforgeeks.org/manachers-algorithm-linear-time-longest-palindromic-substring-part-1/))
10. LeetCode (Medium) - Increasing Triplet Subsequence [[link](https://leetcode.com/problems/increasing-triplet-subsequence/)]
11. LeetCode (Medium) - Missing Ranges [[link](https://leetcode.com/problems/missing-ranges/)]
12. LeetCode (Easy) - Reverse LinkedList [[link](https://leetcode.com/problems/reverse-linked-list/)]
13. LeetCode (Hard) - Reverse LinkedList in k groups [[link](https://leetcode.com/problems/reverse-nodes-in-k-group/submissions/)]
14. LeetCode (Easy) - Sqrt [[link](https://leetcode.com/problems/sqrtx/)]
15. LeetCode (Easy) - Rectangle Overlap [[link](https://leetcode.com/problems/rectangle-overlap/)]
16. LeetCode (Hard) - Interleaving String [[link](https://leetcode.com/problems/interleaving-string/)]
17. LeetCode (Medium) - Merge Intervals [[link](https://leetcode.com/problems/merge-intervals/)]
18. LeetCode (Medium) - Generate Parentheses [[link](https://leetcode.com/problems/generate-parentheses/)]
19. LeetCode (Hard) - LRU Cache [[link](https://leetcode.com/problems/lru-cache/)]
20. LeetCode (Medium) - Search in Rotated Sorted Array [[link](https://leetcode.com/problems/search-in-rotated-sorted-array/)]
21. LeetCode (Medium) - Rotate Image [[link](https://leetcode.com/problems/rotate-image/)]
22. LeetCode (Easy) - Maximum Subarray [[link](https://leetcode.com/problems/maximum-subarray/)]
23. LeetCode (Easy) - Two Sum [[link](https://leetcode.com/problems/two-sum/)]
24. LeetCode (Medium) - Kth Largest Element in an Array [[link](https://leetcode.com/problems/kth-largest-element-in-an-array/)]
25. LeetCode (Medium) - UTF-8 Validation [[link](https://leetcode.com/problems/utf-8-validation/)]
26. LeetCode (Easy) - Count Primes [[link](https://leetcode.com/problems/count-primes/)]
27. LeetCode (Easy) - Climbing Stairs [[link](https://leetcode.com/problems/climbing-stairs/)]
28. LeetCode (Hard) - Maximal Rectangle [[link](https://leetcode.com/problems/maximal-rectangle/)]
29. LeetCode (Medium) - Product of Array Except Self [[link](https://leetcode.com/problems/product-of-array-except-self/)]
30. LeetCode (Easy) - Sum of Two Numbers [[link](https://leetcode.com/problems/sum-of-two-integers/)]
31. LeetCode (Medium) - Validate Binary Search Tree [[link](https://leetcode.com/problems/validate-binary-search-tree/)]
32. LeetCode (Easy) - Add Strings [[link](https://leetcode.com/problems/add-strings/)]
33. LeetCode (Hard) - Trapping Rain Water [[link](https://leetcode.com/problems/trapping-rain-water/)]
34. LeetCode (Medium) - Number of Islands [[link](https://leetcode.com/problems/number-of-islands/)]
35. LeetCode (Medium) - Reverse Words in a String [[link](https://leetcode.com/problems/reverse-words-in-a-string/)]
36. LeetCode (Medium) - Binary Tree Zigzag Level Order Traversal [[link](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/)]
37. LeetCode (Medium) - WordBreak [[link](https://leetcode.com/problems/word-break/)]
38. LeetCode (Hard) - WordBreak II [[link](https://leetcode.com/problems/word-break-ii/)]
39. LeetCode (Hard) - Concatenated Words [[link](https://leetcode.com/problems/concatenated-words/)]
40. LeetCode (Medium) - Partition Equal Subset Sum [[link](https://leetcode.com/problems/partition-equal-subset-sum/)]
41. LeetCode (Medium) - Partition to K Equal Sum Subset [[link](https://leetcode.com/problems/partition-to-k-equal-sum-subsets/)] #TODO
42. LeetCode (Easy) - Reverse Bits [[link](https://leetcode.com/problems/reverse-bits/)]
43. LeetCode (Medium) - Subsets [[link](https://leetcode.com/problems/subsets/)]
44. LeetCode (Easy) - Single Number [[link](https://leetcode.com/problems/single-number/)]
45. LeetCode (Medium) - Single Number II [[link](https://leetcode.com/problems/single-number-ii/)]
46. LeetCode (Easy) - Move Zeroes [[link](https://leetcode.com/problems/move-zeroes/)]
47. LeetCode (Easy) - Add Binary Numbers [[link](https://leetcode.com/problems/add-binary/)]
48. LeetCode (Easy) - Intersection of Two Arrays II [[link](https://leetcode.com/problems/intersection-of-two-arrays-ii/)]
49. LeetCode (Easy) - Valid Palindrome [[link](https://leetcode.com/problems/valid-palindrome/)]
50. LeetCode (Easy) - Valid Palindrome II [[link](https://leetcode.com/problems/valid-palindrome-ii/)]
51. LeetCode (Medium) - ZigZag Conversion [[link](https://leetcode.com/problems/zigzag-conversion/)]
52. LeetCode (Easy) - Palindrome Number [[link](https://leetcode.com/problems/palindrome-number/)]
53. LeetCode (Hard) - Regular Expression Matching [[link](https://leetcode.com/problems/regular-expression-matching/)]
54. LeetCode (Medium) - Container with Most Water [[link](https://leetcode.com/problems/container-with-most-water/)]
55. LeetCode (Easy) - Roman to Integer [[link](https://leetcode.com/problems/roman-to-integer/)]
56. LeetCode (Easy) - Longest Common Prefix [[link](https://leetcode.com/problems/longest-common-prefix/)] 
57. LeetCode (Medium) - Interval List Intersections [[link](https://leetcode.com/problems/interval-list-intersections/)]
58. LeetCode (Easy) - Squares of a Sorted Array [[link](https://leetcode.com/problems/squares-of-a-sorted-array/)]
59. LeetCode (Easy) - K Closest points to the origin [[link](https://leetcode.com/problems/k-closest-points-to-origin/)]
60. LeetCode (Medium) - Shortest Bridge [[link](https://leetcode.com/problems/shortest-bridge/)]
61. LeetCode (Medium) - Random Pick with Weight [[link](https://leetcode.com/problems/random-pick-with-weight/)]
62. LeetCode (Hard) - Consecutive Numbers Sum [[link](https://leetcode.com/problems/consecutive-numbers-sum/)]
63. LeetCode (Hard) - Bus Routes [[link](https://leetcode.com/problems/bus-routes/)]
64. LeetCode (Hard) - Reaching Points [[link](https://leetcode.com/problems/reaching-points/)]
65. LeetCode (Easy) - Construct Quad Tree [[link](https://leetcode.com/problems/construct-quad-tree/)]
66. LeetCode (Hard) - Serialize and Deserialize N-ary Tree [[link](https://leetcode.com/problems/serialize-and-deserialize-n-ary-tree/)]
67. LeetCode (Hard) - Employee Free Time [[link](https://leetcode.com/problems/employee-free-time/)]
68. LeetCode (Hard) - Cherry Pickup [[link](https://leetcode.com/problems/cherry-pickup/)]
69. LeetCode (Medium) - Max Area of Island [[link](https://leetcode.com/problems/max-area-of-island/)]
70. LeetCode (Hard) - 24 Game [[link](https://leetcode.com/problems/24-game/)]
71. LeetCode (Medium) - Find K Closest Elements [[link](https://leetcode.com/problems/find-k-closest-elements/)]
72. LeetCode (Medium) - Print Binary Tree [[link](https://leetcode.com/problems/print-binary-tree)]
73. LeetCode (Medium) - Exclusive Time of Functions [[link](https://leetcode.com/problems/exclusive-time-of-functions/)]
74. LeetCode (Medium) - Task Scheduler [[link](https://leetcode.com/problems/task-scheduler/)]
75. LeetCode (Medium) - 01 Matrix [[link](https://leetcode.com/problems/01-matrix/)]
76. LeetCode (Hard) - Expression Add Operators [[link](https://leetcode.com/problems/expression-add-operators/)]
77. LeetCode (Medium) - The Maze [[link](https://leetcode.com/problems/the-maze/)]
78. LeetCode (Medium) - Validate IP Addreess [[link](https://leetcode.com/problems/validate-ip-address/)]
79. LeetCode (Medium) - Sort Characters By Frequency [[link](https://leetcode.com/problems/sort-characters-by-frequency/)]
80. LeetCode (Easy) - Path Sum III [[link](https://leetcode.com/problems/path-sum-iii/)]
81. LeetCode (Medium) - Reconstruct Itineraries [[link](https://leetcode.com/problems/reconstruct-itinerary/)]
82. LeetCode (Medium) - Flatten a Multilevel Doubly Linked List [[link](https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/)] (DFS)
83. LeetCode (Hard) - Reverse Pairs [[link](https://leetcode.com/problems/reverse-pairs/)] ([Fenwick Trees / BIT Trees](https://www.geeksforgeeks.org/binary-indexed-tree-or-fenwick-tree-2/))
84. LeetCode (Hard) - Optimal Account Balancing [[link](https://leetcode.com/problems/optimal-account-balancing/)] ([Settling Debts Paper/ 3-partition problem - Optimal](http://www.mathmeth.com/tom/files/settling-debts.pdf), [Greedy](https://www.geeksforgeeks.org/minimize-cash-flow-among-given-set-friends-borrowed-money/), [Clique Reduction/BFS, Fastest](https://cs.stackexchange.com/questions/46968/self-reducibility-of-clique))
85. LeetCode (Hard) - LFU Cache [[link](https://leetcode.com/problems/lfu-cache/)] ([OrderedDict used as a queue](https://docs.python.org/3/library/collections.html#collections.OrderedDict))
86. LeetCode (Hard) - Basic Calculator III [[link](https://leetcode.com/problems/basic-calculator-iii/)] (See discussion_basic_Calculator.pdf, [python3 iter](https://docs.python.org/3/library/functions.html#iter))
87. LeetCode (Easy) - Logger Rate Limiter [[link](https://leetcode.com/problems/logger-rate-limiter/)]
88. LeetCode (Medium) - Encode and Decode TinyURL [[link](https://leetcode.com/problems/encode-and-decode-tinyurl/)]
89. LeetCode (Hard) - Number of Islands II [[link](https://leetcode.com/problems/number-of-islands-ii/)]
90. LeetCode (Easy) - Shortest Word Distance [[link](https://leetcode.com/problems/shortest-word-distance/)]
91. LeetCode (Easy) - Intersection of Two Arrays [[link](https://leetcode.com/problems/intersection-of-two-arrays/)]
92. LeetCode (Medium) - Decode Ways [[link](https://leetcode.com/problems/decode-ways/)]
93. LeetCode (Hard) - Longest Consecutive Sequence [[link](https://leetcode.com/problems/longest-consecutive-sequence/)] (UnionFind, Ad-hoc)
94. LeetCode (Medium) - Remove Nth Node From End Of List [[link](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)] (Two Pointers)
95. LeetCode (Hard) - Integer to English Words [[link](https://leetcode.com/problems/integer-to-english-words/)] (Divide and Conquer)
96. LeetCode (Medium) - Fraction to Recurring Decimal [[link](https://leetcode.com/problems/fraction-to-recurring-decimal/)]
97. LeetCode (Medium) - Surrounded Regions [[link](https://leetcode.com/problems/surrounded-regions/)] (BFS)
98. LeetCode (Medium) - Word Ladder [[link](https://leetcode.com/problems/word-ladder/)] (Bi-Directional BFS)
99. LeetCode (Medium) - Spiral Matrix [[link](https://leetcode.com/problems/spiral-matrix/)]
100. LeetCode (Medium) - Clone Graph [[link](https://leetcode.com/problems/clone-graph/)]
101. LeetCode (Medium) - Design Snake Game [[link](https://leetcode.com/problems/design-snake-game/)]
102. LeetCode (Medium) - Multiply Strings [[link](https://leetcode.com/problems/multiply-strings/)]
103. LeetCode (Easy) - Linked List Cycle [[link](https://leetcode.com/problems/linked-list-cycle/)]
104. LeetCode (Easy) - Excel Sheet Column Number [[link](https://leetcode.com/problems/excel-sheet-column-number/)]
105. LeetCode (Medium) - Letter Combinations of a Phone Number [[link](https://leetcode.com/problems/letter-combinations-of-a-phone-number/)] (Backtracking)
106. LeetCode (Hard) - Insert Interval [[link](https://leetcode.com/problems/insert-interval/)]
107. LeetCode (Easy) - Jewels and Stones [[link](https://leetcode.com/problems/jewels-and-stones/)]
108. LeetCode (Medium) - Friend Circles [[link](https://leetcode.com/problems/friend-circles/)] (Union-Find)
109. LeetCode (Medium) - Add and Search Word - Data structure design [[link](https://leetcode.com/problems/add-and-search-word-data-structure-design/)] (Trie)
110. LeetCode (Medium) - Bomb Enemy [[link](https://leetcode.com/problems/bomb-enemy/)] (Dynamic Programming)
111. LeetCode (Medium) - Coin Change [[link](https://leetcode.com/problems/coin-change/)] (Dynamic Programming, DFS)
112. LeetCode (Medium) - Longest Increasing Subsequence [[link](https://leetcode.com/problems/longest-increasing-subsequence/)] (Dynamic Programming, Binary Search)
113. LeetCode (Medium) - Wiggle Subsequence [[link](https://leetcode.com/problems/wiggle-subsequence/)] (Greedy Algorithm)
114. LeetCode (Medium) - Course Schedule [[link](https://leetcode.com/problems/course-schedule/)] ([Detect cycle in a directed graph](https://www.geeksforgeeks.org/detect-cycle-in-a-graph/))
115. LeetCode (Medium) - Course Schedule II [[link](https://leetcode.com/problems/course-schedule-ii/)] ([Topological Sort](https://www.youtube.com/watch?v=ddTC4Zovtbc), Cycle Detection in 114.)
116. LeetCode (Medium) - Word Search [[link](https://leetcode.com/problems/word-search/)] (Backtracking)
117. LeetCode (Medium) - Permutations II [[link](https://leetcode.com/problems/permutations-ii/)] (Backtracking)
118. LeetCode (Medium) - Palindrome Partitioning [[link](https://leetcode.com/problems/palindrome-partitioning/)] (Backtracking)
119. LeetCode (Medium) - Compare Version Numbers [[link](https://leetcode.com/problems/compare-version-numbers/)] (String Manipulation)
120. LeetCode (Medium) - Largest Number [[link](https://leetcode.com/problems/largest-number/)] (Sorting, String/Arrays, custom comparator op)
121. LeetCode (Medium) - Nth Highest Salary [[link](https://leetcode.com/problems/nth-highest-salary/)] (SQL)
122. LeetCode (Medium) - Remove K Digits [[link](https://leetcode.com/problems/remove-k-digits/)] (Greedy Algorithm, Stacks, Monotonically Increasing Sequence)
123. LeetCode (Medium) - Pow(x,n) [[link](https://leetcode.com/problems/powx-n/)] (Divide and Conquer-ish)
124. LeetCode (Medium) - Simplify Path [[link](https://leetcode.com/problems/simplify-path/)] (Stacks)
125. LeetCode (Easy) - Implement strStr() [[link](https://leetcode.com/problems/implement-strstr/)] (String, Rabin Karp Algorithm)
126. LeetCode (Medium) - Distribute Coins in Binary Tree [[link](https://leetcode.com/problems/distribute-coins-in-binary-tree/)] (Depth First Search)
127. LeetCode (Medium) - Decode String [[link](https://leetcode.com/problems/decode-string/)] (String/Stacks)
128. LeetCode (Medium) - Game Of Life [[link](https://leetcode.com/problems/game-of-life/)] (Matrix/Game/Array)
129. LeetCode (Hard) - Word Ladder II [[link](https://leetcode.com/problems/word-ladder-ii/)] (BFS, all shortest paths between two nodes in undirected graph)
130. LeetCode (Hard) - Max Points on a Line [[link](https://leetcode.com/problems/max-points-on-a-line/)] (Array iteration, defining a line, duplicates resolution, checking collinearity)
131. LeetCode (Medium) - Copy List with Random Pointer [[link](https://leetcode.com/problems/copy-list-with-random-pointer/)] (Similar to Clone Graph problem)
132. LeetCode (Medium) - Next Greater Element III [[link](https://leetcode.com/problems/next-greater-element-iii/)]
133. LeetCode (Medium) - Reorder List [[link](https://leetcode.com/problems/reorder-list/)] (Suturing a LinkedList, Stack)
134. LeetCode (Medium) - Restore IP Addresses [[link](https://leetcode.com/problems/restore-ip-addresses/)] (Backtracking)
135. LeetCode (Hard) - Sliding Window Maximum [[link](https://leetcode.com/problems/sliding-window-maximum/)] (Dynamic Programming)
136. LeetCode (Medium) - Partition List [[link](https://leetcode.com/problems/partition-list/)] (LinkedList)
137. LeetCode (Medium) - Pacific Atlantic Water Flow [[link](https://leetcode.com/problems/pacific-atlantic-water-flow/)] (DFS, Similar to Longest Increasing Path in a Matrix)
138. LeetCode (Hard) - Longest Increasing Path in a Matrix [[link](https://leetcode.com/problems/longest-increasing-path-in-a-matrix/)] (DFS, DP/memoization)
139. LeetCode (Easy) - Sum of Root To Leaf Binary Numbers [[link](https://leetcode.com/problems/sum-of-root-to-leaf-binary-numbers/)] (DFS, Bit Manipulation)
140. LeetCode (Medium) - Next Greater Node In Linked List [[link](https://leetcode.com/problems/next-greater-node-in-linked-list/)] (Stack, Arrays)
141. LeetCode (Hard) - Subarrays with K Different Integers [[link](https://leetcode.com/problems/subarrays-with-k-different-integers/)] (Sliding Window)
142. LeetCode (Easy) - Pairs of Songs With Total Durations Divisible by 60 [[link](https://leetcode.com/problems/pairs-of-songs-with-total-durations-divisible-by-60/)] (Hash Table)
143. LeetCode (Easy) - Find the Town Judge [[link](https://leetcode.com/problems/find-the-town-judge/)] (Sets)
144. LeetCode (Easy) - Rotting Oranges [[link](https://leetcode.com/problems/rotting-oranges/)] (BFS)
145. LeetCode (Easy) - Cousins in Binary Tree [[link](https://leetcode.com/problems/cousins-in-binary-tree/)] (BFS)
146. LeetCode (Medium) - Vertical Order Traversal of a Binary Tree [[link](https://leetcode.com/problems/vertical-order-traversal-of-a-binary-tree/)] (BFS, interesting use of lambda/defaultdict and reported order)
147. LeetCode (Medium) - Minimum Cost For Tickets [[link](https://leetcode.com/problems/minimum-cost-for-tickets/)] (Dynamic Programming)
148. LeetCode (Hard) - Unique Paths III [[link](https://leetcode.com/problems/unique-paths-iii/)] (DFS, Dynamic Programming/Bit Manipulation)
149. LeetCode (Medium) - Longest Turbulent Subarray [[link](https://leetcode.com/problems/longest-turbulent-subarray/)] (Arrays)
150. LeetCode (Medium) - Prison Cells After N Days [[link](https://leetcode.com/problems/prison-cells-after-n-days/)] (Bit Manipulation)
151. LeetCode (Medium) - Inorder Successor of BST [[link](https://leetcode.com/problems/inorder-successor-in-bst/)] (Inorder Traversal, BST, Stack)
152. LeetCode (Medium) - Find First and Last Position of Element in Sorted Array [[link](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)] (Python's bisect package, Binary Search)
153. LeetCode (Medium) - Minesweeper [[link](https://leetcode.com/problems/minesweeper/)] (recursive DFS)
154. LeetCode (Easy) - Count and Say [[link](https://leetcode.com/problems/count-and-say/)] (Recursion)
155. LeetCode (Easy) - Delete node in a linked list [[link](https://leetcode.com/problems/delete-node-in-a-linked-list/)] (Trick on LL/ copy the next element to current and delete the next one)
156. LeetCode (Easy) - Merge two sorted lists [[link](https://leetcode.com/problems/merge-two-sorted-lists/)] (Recursion)
157. LeetCode (Easy) - Palindrome Linked List [[link](https://leetcode.com/problems/palindrome-linked-list/)] (O(1) space and O(n) time)
158. LeetCode (Easy) - High Five [[link](https://leetcode.com/problems/high-five/)] (Heap)
159. LeetCode (Medium) - Max Increase to Keep City Skyline [[link](https://leetcode.com/problems/max-increase-to-keep-city-skyline/)] (Smart Iteration)
160. LeetCode (Hard) - Robot Room Cleaner [[link](https://leetcode.com/problems/robot-room-cleaner/)] (Depth First Search)
161. LeetCode (Medium) - Rotate List [[link](https://leetcode.com/problems/rotate-list/)] (Linked List)
162. LeetCode (Hard) - Number of Atoms [[link](https://leetcode.com/problems/number-of-atoms/)] (Hash Table)
163. LeetCode (Medium) - Reverse Words in a String II [[link](https://leetcode.com/problems/reverse-words-in-a-string-ii/)] (in-place transformation)
164. LeetCode (Easy) - Valid Parentheses [[link](https://leetcode.com/problems/valid-parentheses/)] (Stack)
165. LeetCode (Medium) - Add Two Numbers II [[link](https://leetcode.com/problems/add-two-numbers-ii/)] (Stack, reverse linked list)
166. LeetCode (Hard) - Merge k Sorted Lists [[link](https://leetcode.com/problems/merge-k-sorted-lists/)] (Accumulate in list and sort instead of recursion)
167. LeetCode (Easy) - Intersection of Two Linked Lists [[link](https://leetcode.com/problems/intersection-of-two-linked-lists/)] (Stack, Two pointers)
168. LeetCode (Medium) - Binary Tree Inorder Traversal [[link](https://leetcode.com/problems/binary-tree-inorder-traversal/)] (Iterative/recursive inorder)
169. LeetCode (Medium) - Binary Tree Level Order Traversal [[link](https://leetcode.com/problems/binary-tree-level-order-traversal/)] (BFS)
170. LeetCode (Medium) - Populating Next Right Pointers in Each Node [[link](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/)] (BFS, perfect binary tree constraint)
171. LeetCode (Medium) - Populating Next Right Pointers in Each Node II [[link](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/)] (BFS)
172. LeetCode (Easy) - Lowest Common Ancestor of a Binary Search Tree [[link](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/)] (Recursion)
173. LeetCode (Medium) - Lowest Common Ancestor of a Binary Tree [[link](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/)] (Iterative post order traversal using stack)
174. LeetCode (Medium) - Construct Binary Tree from Preorder and Inorder Traversal [[link](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)] (Recursion)
175. LeetCode (Hard) - Alien Dictionary [[link](https://leetcode.com/problems/alien-dictionary/)] (Topological Sort for directed graph)
176. LeetCode (Medium) - Grumpy Bookstore Owner [[link](https://leetcode.com/problems/grumpy-bookstore-owner/)]