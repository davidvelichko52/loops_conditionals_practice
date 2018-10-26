<!--
    Originally adapted from GA-ATX's lab found here:
    https://git.generalassemb.ly/WDIplus-ATX/loops-and-errors
-->


# Loops and Errors

---

Title: Loops and Errors Lab<br>
Duration: 1 hr approx<br>
Creator: Brandi Butler (Inspired by [GA-ATX's lab](https://git.generalassemb.ly/WDIplus-ATX/loops-and-errors) - thank you!)<br>
Topics: Errors, While loops, For Loops<br>

---

## Topics

So far, we have learned about the following topics

* Errors and debugging
* Declaring variables with `let` and `const`
* Boolean expressions
* While loops
* For loops


Let's go over them for a refresher. We will continue to use these concepts throughout the course.

Work through the following prompts in turn:

<br>
<hr>

## Errors

Cut and paste the following code into your text editor (yep, it's the "Cheers" song lyrics). The code is broken -- there are **three errors**. You might already see the errors, but --

Run the code and read the error message in the terminal. Using information from the error message (line numbers, etc.), debug the code and make it work.

At the same time, write a comment below the code that specifies what _type_ of error it was. Example, if you get this:

![](https://i.imgur.com/KRHtmPM.png)

Write

```javascript
// SyntaxError: missing ) after argument list
```

Cut and paste:

```javascript
console.log("Making your way in the world today takes everything you've got.");
console.log("Taking a break from all your worries, sure would help a lot.");
console.log("Wouldn't you like to get away?");
console.log("Sometimes you want to go");
console.log("Where everybody knows your name,");
console.lo("and they're always glad you came.");
console.log("You wanna be where you can see,";
console.log("our troubles are all the same");
console.log("You wanna be where" "everybody knows");
console.log("Your name.");
```

Make it so you do not get any more errors!

<br>
<hr>

## Boolean Expressions
**... and arithmetic**

By just looking at the following expressions, determine in your mind whether or not each will evaluate to **true** or **false**. 

> Remember what you learned about truthy-ness and falsey-ness!

1. `999 > 999`
2. `999 == 999`
3. `999 != 999`
4. `-5 >= -4`
5. `100 <= -100`
6. `20 + 5 < 5`
7. `81 / 9 == 9`
8. `9 != 8 + 1`
9. `"abc" == "abc"`
10. `"a" == "b"`

Now how about some trickier ones...

11. `5 == 5`
12. `5 === 5`
13. `5 == "5"`
14. `5 === "5"`
15. `5`
16. `0`
17. `"a"`
18. `""`
19. `[]`
20. `!!true`

<br>
<hr>

## Operators =, ==, and ===

1. What is the difference between:

the **assignment operator** `=`

and the **equality operator** `==`

?

2. What is the difference between:

this **equality operator** `==`

and this **equality operator** `===`

?

<br>
<hr>

## While Loops: reps and reps

### 1. A thousand ginger chocolate honey patties

Write a *while* loop that will log in the console

```
'Ginger chocolate honey patties'
```

1000 times. You can test it out with a smaller number first, such as 10, and when that works, use 1000.

Make sure you do not run an infinite loop! If you do, kill the process in your Terminal. Oops!


### 2. While loop iterator

Write another *while* loop that counts from 0 to 1000 and will log in the console the current loop number.

> => 0
>
> => 1
>
> => 2
>
> => 3

etc.

### 3. While loop + interpolation

Write another *while* loop that prints a message to the console _and_ interpolates the current loop number. Make it count from 0 to 1000.

> => "Current loop number is: 0"
>
> => "Current loop number is: 1"
>
> => "Current loop number is: 2"
>
> => "Current loop number is: 3"


<br>

**NOTE:** Interpolation is a way of using variables in your string. You can use a set of backticks \` instead of regular quotes, and between the two backticks, put whatever strings and variables you want. For variables, specify them with a dollar sign and curly braces.

```javascript
let name = "Rhonda"
console.log(`Hello ${name}`);
```

<br>
<hr>

## For loops

### 1. For loop printing the iterator

* Write a **for loop** that counts from 0 to 100 and console.logs each number.

### 2. For loop with a silly range

* Write another **for loop** that counts from 7 to 635 (no more, no less!), and console.logs each number.

### 3. Take it to the limit

* Declare a variable `let start = 0`
* Declare a variable `const limit = 100`
* Write a for loop that counts from the value of `start` to the value of `limit`, using those variables in the **control panel** of the loop.

Test the loop thoroughly.

### 4. Use your imagination

* Think of something in real life, or nature, or wherever / whenever that displays **looping** behavior.

Use a **for loop** to model the looping behavior of that thing.

Where does the loop begin? Where should it end? Does it simply count from one number to another? Or does it change or mutate data?

> Protip: Don't have a vivid imagination? Borrow some from your neighbor!

<br>
<hr>

## Conclusion

Congrats! There is no need to submit this lab. We will be going over the answers together soon.

If you have extra time and want more to do, use your **research skills** (Google-fu) to find out more about:

* Using a nested loop (a loop inside another loop)
* A full list of falsey values
* Write a for loop that skips every other number
* What are for..in loops used for?

<br>
<hr>
