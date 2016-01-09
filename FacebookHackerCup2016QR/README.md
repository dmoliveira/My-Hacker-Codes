# Facebook Hacker Cup 2016 Qualification Round
Author: [Oliveira, D. M.](http://www.github.com/dmoliveira)

## 1. Introduction
The Facebook Hacker Cup is an annual worldwide programming competition where hackers compete against each other for fame, fortune, glory and a shot at the coveted Hacker Cup. Here I will put my solutions to problems of this fun competition.

## 2. Problems

- Boomerang Constellations
- High Security
- The Price is Correct
- Text Editor

### 2.1. Boomerang Constellations

The night sky can be modeled as an infinite 2D plane. There are N stars at distinct positions on this plane, the ith of which is at coordinates (Xi, Yi).

A boomerang constellation is a pair of distinct equal-length line segments which share a single endpoint, such that both endpoints of each segment coincide with a star's location.

Two boomerang constellations are distinct if they're not made up of the same unordered pair of line segments. How many distinct boomerang constellations can you spot?

**Input**
Input begins with an integer T, the number of nights on which you look out at the sky. For each night, there is first a line containing the integer N. Then, N lines follow, the ith of which contains the space-separated integers Xi and Yi.

**Output**
For the ith night, print a line containing "Case #i: " followed by the number of boomerang constellations in the night sky.

**Constraints**
1 ≤ T ≤ 50 
1 ≤ N ≤ 2,000 
-10,000 ≤ Xi, Yi ≤ 10,000 


**Explanation of Sample**
On the first night, every pair of stars is a unique distance apart, so there are no boomerang constellations. On the second night, there are 4 boomerang constellations. One of them consists of the line segments (0,0)-(0,2) and (0,2)-(0,4).

Problem [link](https://www.facebook.com/hackercup/problem/910374079035613/)
