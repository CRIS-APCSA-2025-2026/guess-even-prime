# Guess Even & Prime Numbers

Create a program `GuessEvenPrime.java` that creates three objects.
Each object should:

* generate a random integer number
* print the number
* print whether it is *even* or *odd*
* print whether it is prime or not (`true`/`false`)

The project should contain the following features:

* prompt the user for the lower (inclusive) and upper (non-inclusive)
  range of numbers to guess
* proper comments (heading, methods, inline where needed)
* public static (class) method `int randomInt(int lower, int upper)`
* private non-static (instance) variable containing a random integer
* random int initialized in the *constructor*
* public non-static (instance) method `boolean isEven()`
* public non-static (instance) method `boolean isPrime()`
* public static (class) main method

## UML Diagram

```
+------------------------------------------+
|             GuessEvenPrime               |
+------------------------------------------+
|  - randNum: int                          |
+------------------------------------------+
|  + GuessEvenPrime()                      |
| _+ randomInt(int lower, int upper): int_ |
|  + isEven() : boolean                    |
|  + isPrime() : boolean                   |
| _+ main(String[] args) : void_           |
+------------------------------------------+
```

## Example Output

(Indentation should be a single tab (`\t`) character.)

```
Guess random numbers in a range.

Input the lower range (inclusive): 1
Input the upper range (non-inclusive): 20

Random numbers in the range 1 to 20:

Guess #1
    number: 13
    odd
    is prime? true

Guess #2
    number: 10
    even
    is prime? false

Guess #3
    number: 2
    even
    is prime? true
```
