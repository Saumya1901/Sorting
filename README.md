# Sorting Visualizer
----

 [https://sorting-visualizer-saumya-1.netlify.app/][PlDb]

Sorting visualizer website build with HTML, CSS and Javascript ., to visualize sorting algorithms to make the mechanishm of sorting easier to understand.

----
## Features

- Select the Array Size
- Choose any of 4 sorting methods available
- Speed up or down at your own convenience


-----
## Algorithms
- Bubble Sort
- Insertion Sort
- Selection Sort
- Merge Sort
------

## Technology 
- HTML
- CSS
- Javascript
---

## Bubble Sort

Bubble Sort is the simplest sorting algorithm that works by repeatedly swapping the adjacent elements if they are in the wrong order. This algorithm is not suitable for large data sets as its average and worst-case time complexity is quite high.

Degree of Polynomial :- 2

Time Complexity is O(n^2) .

Time Complexity is n^2 because here i used Two itarations .

## Selection Sort

The selection sort algorithm sorts an array by repeatedly finding the minimum element (considering ascending order) from unsorted part and putting it at the beginning. The algorithm maintains two subarrays in a given array.

- The subarray which is already sorted. 
- Remaining subarray which is unsorted.

In every iteration of selection sort, the minimum element (considering ascending order) from the unsorted subarray is picked and moved to the sorted subarray.

The time complexity of Selection Sort is O(N2) as there are two nested loops:

- One loop to select an element of Array one by one = O(N)
- Another loop to compare that element with every other Array element = O(N)

## Merge Sort

The Merge Sort algorithm is a sorting algorithm that is considered an example of the divide and conquer strategy. So, in this algorithm, the array is initially divided into two equal halves and then they are combined in a sorted manner. We can think of it as a recursive algorithm that continuously splits the array in half until it cannot be further divided. 

Time Complexity: O(n log(n)),  Sorting arrays on different machines.

## Insertion Sort

Insertion sort is a simple sorting algorithm that works similar to the way you sort playing cards in your hands. The array is virtually split into a sorted and an unsorted part. Values from the unsorted part are picked and placed at the correct position in the sorted part.

Time Complexity: O(N^2) 

----

