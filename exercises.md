# Numbers, variables, and math.
* What is 123456789 times 987654321?
---
* Create a variable called `mass` that is equal to 100.
* Create a variable called `velocity` that is equal to 5.
* In physics, the momentum an object is exerting is equal to its mass times its velocity. That is, $p = mv$. Use the variables you defined above to compute this object's momentum.
* The kinetic energy of an object is half its mass times the square of its velocity. That is, $K = \frac{1}{2}mv^2$. Compute the kinetic energy for this object using the variables you've already created.
---
* Create a variable called `pi` that is equal to 3.141.
## In the next few exercises, our goal will be to figure out how much icing we will need to perfectly cover our doughnut. The doughnut features a hole (unfortunately no jelly filling), and a few large sprinkles. You do not need to cover the place below sprinkles with icing.
<!-- TODO: Donut image -->
* Create the variables `R`, `r`, and `s`, as shown in the image.
* Find the area of the larger circle (the whole doughnut, including the hole). Call this variable `area_big_circle`.
* Find the area of the smaller circle (the hole). Call this variable `area_small_circle`.
* Find the area of one triangle (a sprinkle). Call this variable `area_sprinkle`.
* Using the three values you calculated above, find the area of the shaded region (i.e., how much icing will you need?). Save the result in a variable called `area_donut`.

# Strings
* Create a variable called `name` that is equal to your name.
* By adding strings together, introduce yourself in a string. For example `"Hello, my name is Tim!"`. You may use f-strings if you know what they are and prefer to use them.
* Define the string `fact` to be `"Python programming is fun."`
* Index `fact` in order to get the "o" in "Python".
* Index `fact` in order to get the "u" in "fun" using a negative index.
* Slice `fact` in order to get the word "programming".
* Uppercase `fact`.
* Replace the period at the end of `fact` with an exclamation point.
* Use `.split()` to get the second word of this string. Was this easier than one of the problems above?
* Reverse `fact`.
* Does `fact` contain the letter `y`? To find this answer, use the `in` keyword.
* How many `o`s does `fact` have?
* Replace all the `o`s in `fact` with an underscore (do not redefine `fact`).

# Lists
* Create a list `friends` of your three best friends, `"Alice"`, `"Bob"`, and `"Charlie"`.
* Find the length of `friends`.
* Add your new friend, `"Debbie"` to your list of `friends`.
* Charlie has no-showed to your piano recital. Remove him from your `friends`.
* Using the `.join()` method, join `friends` to look like this _exactly_: `"Alice & Bob & Debbie"`
* What is the length of `[]`? What about `[[]]`? Why?

`nested_deep = [1, [2, 3], 4, [5, [6, 7, [8]]]]`

* What is the length of `nested_deep`?
* Index `nested_deep` to get the 5.
* Index `nested_deep` to get the 8.

# Conditionals and Loops
* Print out the numbers 1 through 10.
* Print out the even numbers between 1 and 20 by using the third paramter to the `range()` function.
* Print out the even numbers between 1 and 20 by checking if the number is even before printing.
* What is the sum of the first 100 integers? Hint: Create a variable `total` equal to zero, and increment `total` inside a loop.
* For each friend in your `friends` list above, print `"PERSON IS AWESOME!"` in all caps, where `PERSON` is of course replaced with your friend's name.
* Similar to the last problem, print `"PERSON IS AWESOME!"` for each friend in your friends list _only if their name ends in a vowel_. Otherwise, print `"person is ok..."` (all lowercase). 
* For each number between 1 and 30, if a number is divisible by 3, print `"Fizz"`. Otherwise, just print the number.
* For each number between 1 and 30, if a number is divisible by 5, print `"Buzz"`. Otherwise, just print the number.
* For each number between 1 and 30,
    - if a number is divisible by 3, print `"Fizz"`
    - if a number is divisible by 5, print `"Buzz"`
    - if a number is divisible by both 3 and 5, instead print `"Fizzbuzz"`,
    - otherwise, just print the number
This problem is the famous "Fizzbuzz" problem - and is a very common interview coding challenge! If you can do this without help, you're making awesome progress! Well done!
* Define some string `sentence`. If you can't think of a good one, feel free to use `fact` above.
* Count the number of vowels in `sentence` (no, y is not a vowel).
* Define a variable `sentence_rm` that is equal to `sentence` with all vowels removed. Hint: This is a tough one. Start out with an empty string and concatenate all of the consonants to it inside a loop.
* Create a variable `fav_number` equal to whatever is your favorite integer. Write a loop to determine if `fav_number` is prime. Recall that a prime number is any number whose only divisors are 1 and itself. For example, 6 is not prime since it's divisible by 1, 2, 3, and 6. But 7 _is_ prime since it's only divisible by 1 and 7.
* A palindromic number reads the same both ways. For example, 1234321 is a palindrome. The largest palindrome made from the product of two two-digit numbers is 9009 = 91 × 99. Find the largest palindrome made from the product of two three-digit numbers.

# List Comprehensions
### Disclaimer:
Many (maybe all) of these exercises can be done without a list comprehension. However, listcomps are often the easiest way to solve a problem like this. Listcomps are also optimized in Python, meaning they are also often the _fastest_ way to solve a problem.

* Create a list of the numbers 1 through 10.
* Create a list of the squares of the numbers between 1 and 10.
* Create a list of all the even numbers between 18 and 47.
* Create a list of the squares of the even numbers between 1 and 20.
* What is the sum of the cubes of the numbers between 5 and 10?
* Create a list of all of the numbers divisible by either 3 or 5 (or both) between 1 and 30.
* Let `friends = ["Alice", "Bob", "Charlie", "Derek"]`. Redefine this list to be all uppercase.
* Remove all elements from `friends` whose names do not end in a vowel.
* You need to access Excel files that have names like `Jan 5.xlsx` or `Mar 15.xlsx`. Create a list of January 1 through January 31 like this. That is, create the list of: `["Jan 1.xlsx", "Jan 2.xlsx", ... , "Jan 31.xlsx"]`.
* Take the string `"avocado"` and redefine it to be `"aVoCaDo"`. (That is, capitalize only the consonants). (Hint: You'll find the `.join()`) method to be useful here.)

# Functions
* Write a function to compute the area of a triangle. You only need the base and height of a triangle to compute its area.
* Import `pi` from `math` and write a function to compute the area of a circle. You only need the radius of a circle to compute its area.
* Write a function that takes in a number `n` and returns the sum of the numbers 1 through `n`.
* Write a function that takes in a number `n` and returns the sum of the square of the numbers 1 through `n`.
* Write a function that takes a list of amounts in euros, and returns them converted to dollars. (You did this in Section V)
* Write a function that takes a list of heights and returns "Tall enough" if they are at least 5 feet (60 inches) or "Too short" if they are below 5 feet.
* Write a function that takes in a numeric grade (0 to 100) and returns the letter grade (no pluses or minuses). In a traditional rubric, that would be as follows:
    * 90 or above = A
    * 80 - 89 = B
    * 70 - 79 = C
    * 60 - 69 = D
    * 59 or below = F
* Write _another_ function that takes a list of numeric grades and returns their letter grades. Use the function written above in your answer.

* Write a function that takes in a string and returns the number of vowels in that string.
* Write a function that takes in a string and returns that string with its consonants capitalized and vowels lowercased.
* Write a function that takes in a string and returns that string with its vowels removed.
* Write a function that takes in a string (likely multiple words long) and returns that string with each word reversed, but with the words in the same order.

* Write a function that converts a string to "leet speak". Leet speak is a made-up internet language which you replace characters with symbols that look like those characters. For example:

Example: `to_leet_speak("i am elite") --> "! @M 31!73"`

Below is the English-to-leet dictionary:

```
leet_dict = {'A' : '@', 'B' : '8', 'C' : '(', 'D' : 'D', 'E' : '3',
             'F' : 'F', 'G' : '6', 'H' : '#', 'I' : '!', 'J' : 'J',
             'K' : 'K', 'L' : '1', 'M' : 'M', 'N' : 'N', 'O' : '0',
             'P' : 'P', 'Q' : 'Q', 'R' : 'R', 'S' : '$', 'T' : '7',
             'U' : 'U', 'V' : 'V', 'W' : 'W', 'X' : 'X', 'Y' : 'Y',
             'Z' : '2'}
```

This problem is borrowed from [this](https://www.codewars.com/kata/toleetspeak) wonderful Codewars challenge!

* Write an `is_prime` function that takes in a number and returns a boolean of whether or not that number was prime. (Hint: You already did this)

* Write a function that takes in a number and returns the sum of all primes less than or equal to that number.








