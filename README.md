# Learn How to Work with Numbers and Strings by Implementing the Luhn Algorithm

Following along with freeCodeCamp's _[Learn How to Work with Numbers and Strings by Implementing the Luhn Algorithm]()_ lesson -- part of the **Scientific Computing with Python** certification.

### Description

> _The Luhn Algorithm is widely used for error-checking in various applications, such as verifying credit card numbers._
>
> _By building this project, you'll gain experience working with numerical computations and string manipulation._


#### The Luhn algorithm is as follows:

1. From the right to left, double the value of every second digit; if the product is greater than 9, sum the digits of the products.
2. Take the sum of all the digits.
3. If the sum of all the digits is a multiple of 10, then the number is valid; else it is not valid.

Assume an example of an account number "7992739871" that will have a check digit added, making it of the form 7992739871x:

**Example Code**
```
Account number      7   9  9  2  7  3  9   8  7
1  x
Double every other  7  18  9  4  7  6  9  16  7
2  x
Sum 2-char digits   7   9  9  4  7  6  9   7  7
2  x
```
