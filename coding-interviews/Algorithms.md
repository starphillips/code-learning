
# Search
### Binary Search

Halfing the search results each time
Works for sorted lists


### Depth First Search

Search all the way down a tree, going with the left first.
Example: maze

### Breadth First Search

Search all nodes at one level before moving to the next

neighbours = []
visited = []

take the first node and gather its neighbours
visit the first neighbour and add their neighbours to the end of the list
visit the next neighbour who was at the front of the queue

example: chess - chooses all the possible moves, then all the possible moves of those moves

# Sort

### Insertion Sort
Recursive / divide and conquer

Best when lists are already sorted (or small)
Goes through each element and compares against whether it is > previous 

Time complexity:
W: O(n^2)
B: O(n) - when its already sorted it just goes through them


### Merge Sort
Breaking into parts and into pairs, sorts between the pairs for whose bigger and smaller
Then finds the next pair and sorts between bigger and smaller, up until they reach the original sized array

Best and Worst: O(nlogn)

Better for larger and unsorted


### Quick Sort
Recursive / divide and conquer

Find a median - move to end of the list
Compare the first and last element
if left > right - swap them
if left < right - keep the same
until the two pointers meet
then swap the median (which is kept at the end) with the middle element
Then with the separate lists, we choose a median pivot again and sorting the same way

Best O(nlogn)
Worst O(n^2)

Average the fastest when its the best used

# Greedy
Every time they have to make a decision they look at the best decision currently.

When a problem is complex - go greedy