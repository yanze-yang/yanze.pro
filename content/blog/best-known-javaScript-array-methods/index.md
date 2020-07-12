---
title: Best-Known JavaScript Array Methods
date: "2020-07-01"
description: This is a custom description for SEO and Open Graph purposes, rather than the default generated excerpt. Simply add a description field to the frontmatter.
---

```toc
# This code block gets replaced with the TOC
```

## Array.prototype.every()

> arr.every(callback(element[, index[, array]])[, thisArg])

The every() method tests whether
🌟all elements in the array
🌟pass the test implemented by the provided function.
It returns a Boolean value.

Given an array, write a function to check if all elements of that array are less than 100 or not.

```javascript{numberLines: true}
function fnIsLessThan100_Every(arr) {
  return arr.every(element => element < 100) // highlight-line
}
fnIsLessThan100_Every([30, 60, 90]) // true
fnIsLessThan100_Every([10, 40, 89, 120]) // false
```

> arr.every(callback(element[, index[, array]])[, thisArg])

The every() method tests whether
🌟all elements in the array
🌟pass the test implemented by the provided function.
It returns a Boolean value.

Given an array, write a function to check if all elements of that array are less than 100 or not.

```javascript{numberLines: true}
function fnIsLessThan100_Every(arr) {
  return arr.every(element => element < 100) // highlight-line
}
fnIsLessThan100_Every([30, 60, 90]) // true
fnIsLessThan100_Every([10, 40, 89, 120]) // false
```

## Array.prototype.some()
