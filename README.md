# ads-assignment1

For the assignments below use only primitive data types, `String` variables and fixed size array data structures. 

### Fibonacci Calls Count (2 points)

+ Create a class `Fibonacci`.
+ Implement a static method `int fib(int n)` inside the class that computes the n-th Fibonacci number (Fibonacci numbers start like this: $0, 1, 1, 2, 3, 5 ...$ ).
+ Recursive method `int fib(int n)` should also count the number of times it was called. (Hint: a static variable can be used).
+ Write a testing program in the `main` method of `Fibonacci` class to test the `fib` method.

### Big Factorial (3 points)
+ Create a class `BigFactorial`.
+ Implement the `factorial` method that returns the factorial of an integer using recursion.
+ The method has the following signature `BigInteger factorial(int n)`.
+ Write a program in the `main` method of `BigFactorial` class that prompts the user to enter an integer and displays its factorial.


### Sum Series (3 points)
+ Create a class `SumSeries`.
+ Write a recursive method `double sum1(int i)` to compute the following series:
$1 + \frac{1}{2} + \frac{1}{3} + ... + \frac{1}{i}$
+ Write a recursive method `double sum2(int i)` to compute the following series:
$1 + \frac{1}{2} + \frac{1}{3} + ... + \frac{1}{i}$
+ Write a recursive method `double sum3(int i)` to compute the following series:
$1 + \frac{1}{2} + \frac{1}{3} + ... + \frac{1}{i}$
+ Write a test program in the `main` method of `SumSeries` class to test the three methods.

### Reverse Integer (2 points)
+ Create a class `ReverseInteger`.
+ Inside the class write a recursive method `int reverse(int n)` that reverses it's argument. For example, `reverse(123)` returns `321`.
+ Write a test program in the `main` method of `ReverseInteger` class to test the `reverse` method.

### Digit Sum (2 points)
+ Create a class `DigitSum`.
+ Inside the class write a recursive method `int sum(int n)` that returns the sum of digits of it's argument.
+ Write a test program in the `main` method of `DigitSum` class to test the `sum` method.

### Reverse String (2 points)
+ Create a class `ReverseString`.
+ Inside the class implement a recursive method `String reverse(String s)` that returns the reverse of it's argument.
+ Write a test program in the `main` method of `ReverseString` class to test the `reverse` method.

### Palindrome (2 points)
+ Create a class `Palindrome`.
+ Inside the class implement a recursive method `boolean isPalindrome(String s)` that returns `true` if it's argument is a palindorme, and returns `false` otherwise.
+ Write a test program in the `main` method of `Palindrome` class to test the `isPalindrome` method.
  
### Decimal to BinaryString (2 points)
+ Create a class `DecimalBinary`.
+ Inside the class implement a recursive method `String dec2bin(int n)` that returns the binary representation of the decimal.
+ Write a test program in the `main` method of `DecimalBinary` class to test the `dec2bin` method.
  
### BinaryString to Decimal (2points)
+ Create a class `BinaryDecimal`.
+ Inside the class implement a recursive method `int bin2dec(String s)` that returns the decimal representation of the binary string.
+ Write a test program in the `main` method of `BinaryDecimal` class to test the `bin2dec` method.
  
### String Permutations (5 points)
+ Create a class `StringPermution`.
+ Inside the class implement a method `void printPermutations(String s)` that prints all the perumations of the string characters.
+ Use recursive helping methods of your own to solve the problem.
+ `printPermutations` is not recursive, it's just a wrapper around your own recursive method.
+ Write a test program in the `main` method of `StringPermutation` class to test the `printPermutations` method.
+ For example, `printPermutations("abc")` prints:
  ```
  abc
  acb
  bac
  bca
  cab
  cba
  ```
