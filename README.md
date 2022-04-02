# Instertion Sort Project
It is mock-up project to understand how the insertion sorting algorithm work, presented in Kodluyoruz's 'Data Structure and Algorithms' lecture. 

Sort the **[22,27,16,2,18,6]** in principles with insertion sorting.

**[2, 22, 27, 16, 18, 6]** ➔ Sorted the n elements of the array.
**[2, 6, 22, 27, 16, 18]** ➔ n-1
**[2, 6, 16, 22, 27, 18]** ➔ n-2
**[2, 6, 16, 22, 18, 27]** ➔ 1
 ---
 For an n numbered array, the formula to find the number of actions by the algorithm will be equal to (n^2+n)/2.
 In Big O notation, the dominant number is chosen by which operand affects the rate of growth most, without constant numbers. Thus, this sorting algorithm's Big O notation will be equal to ➔ O(n^2)
 
 ---

### Worst Case Scenario 
When analyzing algorithms, the average case often has the same complexity as the worst case. So insertion sort, on average, takes ➔ O(n^2)  time.
### Best Case Scenario
Best case scenario for the insertion sort is the case which array come sorted. In this case, number of action taken by the computer will be equal to length of the numbers included in array. ➔ O(n)

---
### Which case would be in if the number '18' after the insertion?

Since the worst case is the one the number we are searching for is at the end of the array, furthermore the average case has the same approach as the worst case, but the number is not at the end of the array, it should be evaluated as the average case.

---

Write the first 4 steps of [7, 3, 5, 8, 2, 9, 4, 15, 6] according to Insertion Sort.

 [7, 3, 5, 8, 2, 9, 4, 15, 6] 

**[2, 7, 3, 5, 8, 9, 4, 15, 6]**

**[2, 3, 7, 5, 8, 9, 4, 15, 6]**

**[2, 3, 4, 7, 5, 8, 9, 15, 6]**

**[2, 3, 4, 5, 7, 8, 9, 15, 6]**# insertionSortProject
