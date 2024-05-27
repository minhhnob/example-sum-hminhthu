# example-sum-hminhthu

<p>Welcome to <strong>example-sum-hminhthu</strong>, a simple JavaScript library that provides utility functions to work with objects, arrays, and perform basic arithmetic operations.</p>

## Installation

<pre>
<code>
npm install example-sum-hminhthu
</code>
</pre>

## Usage

<p>First, import the required functions from the library:</p>

<pre>
<code>
const { areObjects, areArrays, sum } = require('my-library');
</code>
</pre>

### Checking if Two Items are Objects

<p>You can use the <code>areObjects</code> function to check if two items are objects:</p>

<pre>
<code>
const obj1 = { a: 1 };
const obj2 = { b: 2 };
console.log(areObjects(obj1, obj2));  // Output: true
</code>
</pre>

### Checking if Two Items are Arrays

<p>You can use the <code>areArrays</code> function to check if two items are arrays:</p>

<pre>
<code>
const arr1 = [1, 2, 3];
const arr2 = [4, 5, 6];
console.log(areArrays(arr1, arr2));  // Output: true
</code>
</pre>

### Summing Three Numbers

<p>The <code>sum</code> function allows you to sum three numbers:</p>

<pre>
<code>
const result = sum(1, 2, 3);
console.log(result);  // Output: 6
</code>
</pre>

## API

### areObjects(obj1, obj2)

<p>Checks if <code>obj1</code> and <code>obj2</code> are both objects.</p>

<ul>
  <li><strong>obj1</strong> (any): The first item to check.</li>
  <li><strong>obj2</strong> (any): The second item to check.</li>
  <li><strong>Returns</strong>: <code>true</code> if both items are objects, otherwise <code>false</code>.</li>
</ul>

### areArrays(arr1, arr2)

<p>Checks if <code>arr1</code> and <code>arr2</code> are both arrays.</p>

<ul>
  <li><strong>arr1</strong> (any): The first item to check.</li>
  <li><strong>arr2</strong> (any): The second item to check.</li>
  <li><strong>Returns</strong>: <code>true</code> if both items are arrays, otherwise <code>false</code>.</li>
</ul>

### sum(a, b, c)

<p>Sums three numbers <code>a</code>, <code>b</code>, and <code>c</code>.</p>

<ul>
  <li><strong>a</strong> (number): The first number.</li>
  <li><strong>b</strong> (number): The second number.</li>
  <li><strong>c</strong> (number): The third number.</li>
  <li><strong>Returns</strong>: The sum of the three numbers.</li>
</ul>

