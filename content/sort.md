{% include navigation.html %}

# Sort, Search-Linear/Binary
## Sorting
A list of indices that is arranged in a specific order (eg. increasing numerical or alphabetical).  It is necessary that lists are sorted for binary searches to be able to work on them.

## Linear Search
A search that goes "from A to Z" through a list, starting at the first indice and ending at the last, or when the desired entry has been located.  It is the most simple form of searching but is extremely inefficient, especially in large lists.

![image](https://user-images.githubusercontent.com/82109882/151615088-a2c26869-f3df-4f6f-9973-aab3c8e8fb58.png)

## Binary Search
An efficient searching algorithm for sorted lists that selects the indice halfway through the list, compares it to the desired value, and then places another halfway mark between the center and the side of the last where the data is located, repeating the process until the data is found, halving the list with each iteration.  It is often condsidered to be very efficient for its simplicity
