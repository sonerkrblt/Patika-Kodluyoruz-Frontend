## Insertion Sort
[22,27,16,2,18,6] -- Let's sort by Insertion Sort. The smallest number is chosen first.
(2) The number 2 is replaced by 22. (2,27,16,22,18,6)
Replaces the other smallest number, 6 - 27. (2,6,16,22,18,27)
Then the other number 16 is checked, but it is in the correct position.
At another stage, the number 18 is looked at. Replaces with 22. (2,6,16,18,22,27)
The number 22 is checked, but it is in the right place in terms of location. 
The number 27 is also correct in location. The latest ranking is as follows. (2,6,16,18,22,27)
Big-O representation = O(n²) Average Case since 18 is in the middle.
The first four steps of the sequence [7,3,5,8,2,9,4,15.6] are as follows.
The smallest number 2 is chosen. It replaces the number 7.
(2,3,5,8,7,9,4,15,6) The other smallest number 3 is chosen. Since its position is correct, it is passed to the next smallest number.
The other smaller number 4 is chosen. Replaces with 5.
(2,3,4,8,7,9,5,15,6) The other smaller number 5 is chosen. It replaces the number 8.
(2,3,4,5,7,9,8,15.6,) The first four steps are like this.
After the other steps are done, the final state is as follows. (2,3,4,5,6,7,8,9,15)

## Merge sort
[16,21,11,8,12,22] divide into two equal parts
[16,21,11] - [8,12,22] resplit elements single
[16] - [21] - [11] -- [8] - [12] - [22] start sorting after this step
[16], [11,21] -- [8,12], [22]
[11,16,21], [8,12,22] sort whole array
[8,11,12,16,21,22] sorting completed.
Big-O = O(nlogn)

## BinarySearchTree

Write steps [7, 5, 1, 8, 3, 6, 0, 9, 4, 2]
Let's root the number 5

                                   5
                                  / \
                                 4   7
                                /    / \
                               3     6  8
                              /          \
                             2            9
                            /
                           1
                          /
                         0 