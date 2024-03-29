# Daily Coding Problems

Welcome to my Daily Coding Problems repository! Here, you'll find my solutions to various coding challenges.

## Day 1

### Problem 1: Format Printing

**Task:** Print the given lines in the same format as provided.

```plaintext
Recently I heard that you’ve achieved 95% marks in your exam.
This is brilliant!
I wish you’ll shine in your life!	Good luck with all the barriers(/\\) in your life.
```

### Problem 2: Arithmetic Operations
**Task:** Take two integers as input and display their sum, difference, product, and quotient in the specified format.

```plaintext
For example:
Inputs are 5 and 2
Then you’ll give output as:
5 + 2 = 7
5 - 2 = 3
5 * 2 = 10
5 / 2 = 2.50
```


### Problem 3: Odd or Even
**Task:** তোমাকে একটি অঋণাত্মক (০ বা এর থেকে বড়) সংখ্যা নিতে হবে এবং বলতে হবে সংখ্যাটি জোড়(even) নাকি বিজোড়(odd)


### Problem 4:
**Task:** তোমাকে একটি ইন্টিজার ভ্যেলু ইনপুট নিতে হবে এবং বলতে হবে এটি ধনাত্মক(positive) নাকি ঋণাত্মক(negative) নাকি শূণ্য(zero)।


### Problem 5:
**Task:** ধরো তোমার এক বন্ধু তোমাকে বলেছে সে একটি Gucci Bag কিনবে যদি তার কাছে ১০ হাজার টাকা বা এর বেশি থাকে। নাহলে যদি তার কাছে ৫ হাজার বা এর বেশি টাকা থাকে তাহলে সে Levis Bag কিনবে। আর নাহলে সে নিউ মার্কেট থেকে কিছু (Something) কিনে নিবে। সে তোমাকে আরও বললো যে, যদি সে Gucci Bag কিনতে পারে এবং তার কাছে যদি ২০ হাজার টাকা এর বেশি থাকে তাহলে সে আরও একটি Gucci Belt কিনবে।
এখন ধরো তুমি জানো তোমার বন্ধুর কাছে কত টাকা আছে, তুমি কি বলতে পারবে সে কোন কোন জিনিস গুলো কিনবে?


### Solution:
- File: [day_1.js](day_1.js)

## Day 2

### Problem 1: Array Filtering and Mapping
**Task:** Create an array of objects, each representing a person with properties like name, age, and gender. Write a function to filter out all females and then map the remaining people to an array of names. Print the final result.

### Problem 2: Object Manipulation
**Task:** Create an array of objects representing books with properties like title, author, and year. Write a function that takes the array and returns a new array with only the book titles. Print the result.

### Problem 3: Function Composition
**Task:** Write three functions: one to square a number, one to double a number, and one to add 5 to a number. Compose these functions to create a new function that squares a number, doubles the result, and then adds 5.
Task: Sorting Objects

### Problem 3: Function Composition
**Task:** Create an array of objects representing cars with properties like make, model, and year. Write a function to sort the array of cars by the year of manufacture in ascending order. Print the sorted array.

### Problem 3: Find and Modify
**Task:** Write a function that searches an array of objects for a specific person by name. If found, modify their age property. Print the updated array.

### Solution:
- File: [day_2.js](day_2.js)

## Day 3

### Problem 1: Object Transformation
**Task:** Create an array of objects representing customers with 'name', 'purchases', and 'loyaltyPoints' properties. Write a function to transform the array by doubling the 'loyaltyPoints' of customers with more than 5 purchases.

### Problem 2: Function Memoization
**Task:** Implement a memoization function that caches the results of expensive function calls and returns the cached result when the same inputs occur again.

### Problem 3: Object Sorting with Multiple Criteria
**Task:** Create an array of objects representing products with 'name', 'price', and 'category' properties. Write a function to sort the array first by 'category' in ascending order and then by 'price' in descending order within each category.

### Problem 4: Function Composition
```plaintext
const array1 = [1, 2, 3, 4, 5];
const array2 = [3, 4, 5, 6, 7];
console.log(findUniqueElements(array1, array2)); 
Output: [1, 2, 6, 7]
```
**Task:** Demonstrate the workflow of the function being used here to find out unique from 2 array

### Problem 5: Find and Modify
**Task:** Review this JavaScript code . The function mysteryFunctionX takes a number as input and creates an array representing a mysterious sequence up to that number. Can you decipher what this function does? Additionally, what would be the output for the provided example (mysteriousNumberX)?

```plaintext
function mysteryFunctionX(limitX) {
const sequenceX = [1];
for (let x = 1; x <= limitX; x++) {
sequenceX[x] = x * sequenceX[x - 1];
}
  return sequenceX;
}

 // Example usage:
const mysteriousNumberX = 5;
console.log(mysteryFunctionX(mysteriousNumberX));
 // Output: [1, 1, 2, 6, 24, 120]
```

### Solution:
- File: [day_3.js](day_3.js)
