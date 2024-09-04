# Mergesort

Implement an iterative (no recursive calls) and in-place version of mergesort.
Use the template I've provided in `code.js`. Test your new function; I've
provided some basic testing code that uses
[jsverify](https://jsverify.github.io/) in `code.test.js`.

Hint: To make merge sort in-place, think about what happens during the merge --
where are elements moved to and from? To make it iterative, think about the
part of the array each recursive call considers.

## Runtime Analysis

Analyse the time complexity of your implementation and give a $\Theta$ bound for
its worst-case runtime. Add your answer, including your reasoning, to this
markdown file.


Recall mergesort:
Mergesort is a “divide and conquer” algorithm.
1. If the array has 0 or 1 elements, it’s sorted. Stop.
2. Split the array into two approximately equal-sized halves.
3. Sort each half recursively (using Mergesort).
4. Merge the sorted halves to produce one sorted result:


