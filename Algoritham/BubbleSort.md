# Bubble Sort Algorithm

Bubble sort is a sorting algorithm that compares two adjacent elements and swaps them until they are in the intended order.

Imagine you have a set of numbered cards that are all mixed up. With bubble sort, you start at one end and look at pairs of cards. If a card with a smaller digit is in front of a card with a larger number, you swap their places.

It’s called “bubble” sort because this is like bubbles rising in water, the smaller numbers gradually move upwards in the list, each one finding its way to the correct place.

This keeps occurring until all the cards are in order—just like when all the bubbles reach the water’s surface, and everything’s resolved. That’s the bubble sort algorithm.


## Bubble Sort Algorithm

```python
bubbleSort(array)
  for i <- 1 to indexOfLastUnsortedElement-1
    if leftElement > rightElement
      swap leftElement and rightElement
end bubbleSort
```
