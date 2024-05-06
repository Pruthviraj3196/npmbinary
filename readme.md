## Readme.md
# Binary Search Package

This package provides a simple implementation of the binary search algorithm.

## Installation
You can install the package using npm:


## Usage:
const { binarySearch } = require('binary-search-package');

const arr = [1, 2, 3, 4, 5, 6, 7, 8, 9];
const target = 5;
const index = binarySearch(arr, target);

if (index !== -1) {
    console.log(`Element found at index ${index}`);
} else {
    console.log('Element not found');
}


