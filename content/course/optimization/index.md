---
title: 'Optimization'
date: 2019-01-01T00:00:00+10:00
weight: 105
---

During crisis response, resources are limited. In a short amount of time, first responders need to evaluate the situation they are in and decide on the most efficient plan of action to respond to crises. The Remote Sensing course discusses optimization problems and optimization algorithms to maximize the effect of data analysis and operations.

## Topics Covered

1. Decision making
   1. What decisions need to be made in HADR applications?
   2. Who makes those decisions?
   3. What information is necessary to support decisions?
   4. What costs/benefits/constraints are considered?
   5. What is optimization? What kind of optimization problems are there?
   6. How to sort data?
2. What optimization problems can be done on graphs?
   1. What is optimization?
   2. Why is optimization difficult?
   3. Combinatorial difficulty, integer problems
   4. What kinds of optimization problems are there?
      1. Shortest path problems
      2. Routing problems
      3. Sensor placement/knapsack
3. Traveling salesman problem (TSP)?
   1. What approaches are there to TSP?
   2. What variations are there of TSP?
   3. How to implement a solution to TSP (greedy) in python (networkx)
   4. How to improve on greedy solution
4. Knapsack problem
   1. Formulation
   2. Applications in real world: budgets, scheduling
   3. Approaches: greedy, discuss edge cases where greedy fails
5. What are job-shop scheduling problems (JSP)?
   1. How can they be represented on a graph?
   2. What can be modeled as JSP?
   3. What approaches can you take for JSP?
   4. How to implement a solution to JSP? How to improve?
6. Exercise: implement greedy approach, see if they can improve
   1. Lecture + Teambuilding exercise: Sorting algorithms
   2. Teambuilding exercise, phase I: students are to line up by age, increasing. Timed.
   3. Lecture: sorting algorithms
       1. big O() complexity
       2. data structures
       3. simple sort algorithms, incl. heapsort
   4. Teambuilding part II: each student is given a random number, need to sort by number, increasing. Timed again.
   5. Discussion – were they able to improve on their time from part I?
      1. Part III: repeat one last time the sorting exercise, except the students get to discuss and plan for up to 5 minutes beforehand. They get new random numbers, and have to sort again.
   6. Discussion, were they able to improve given prep time? What things helped/didn&#39;t help?
      1. Goal of part I -\&gt; part II is to teach the benefit of doing things with more efficient algorithm. Goal of part II -\&gt; part III is the teach benefit of communication, planning, and setting responsibilities.