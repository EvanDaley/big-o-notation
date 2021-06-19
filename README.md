# big-o-notation

A simple explanation of Big O Notation. This isn't comprehensive, but should help you get a basic idea of how it works, and how you can approach certain questions.

Setting the stage - imagine you have an array with `n` elements, and you have some code that does something to that array. The length of time it takes the program to run might be proportional to the length of the array. If the array has 100 items, and you loop over the array 100 times, you are doing roughly 10,000 operations. Looking at Big O Notation gives you a way to classify that operation. Generally O(n) is considered okay, and O(n^2) is bad!

If someone asks about time complexity, they want you to categorize the code in one of these groups:

- O(1) - Constant time complexity
- O(n) - Linear time complexity
- O(log n) - Logarithmic time complexity
- O(n^2) - Quadratic time complexity

# Constant Time: O(1)
This is a simple operation that runs immediately, regardless of the length of the array.

```
console.log("The first item is:", items[0])
```

# Linear Time: O(n)
Imagine you have an array of numbers and you want to double each item. To do that, you would just need to touch each number once. 

The length of time it takes the program to run is proportional to the length of the array. 15 items means your program does roughly 15 operations. As the length of the array goes up, so does the execution time.

![Linear Time](linear.png)

# Logarithmic Time: O(log n)


# Quadratic Time: O(n^2)





