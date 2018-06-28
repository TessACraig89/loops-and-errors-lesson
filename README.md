
# WDIplus-ATX

---

Title: Afternoon Lab<br>
Duration: 1 hr 15 mins approx<br>
Creator: Alex White <br>
Topics: Terminal, Errors, While loops, For Loops<br>

---

# Afternoon Lab

## Topics

Today we had a look at

* Terminal
* Errors
* Variables with `let` and `const`
* DRY
* Boolean expressions
* While loops
* For loops


Let's go over them for a refresher. We will be returning to them throughout the course.

Work through the following prompts in turn:

<br>
<hr>

# Terminal

* Open Terminal

* Navigate to your Documents directory `/User/username/Documents`

* Make a **directory** inside Documents called `w1d1_lab`

* Go into the `w1d1_lab` directory

* Inside `w1d1_lab`, make a file called `first_lab.js`

* Open the `w1d1_lab` directory in your text editor

Write the answers to the rest of this lab in the `first_lab.js` file.

Make sure you are in the same directory as the file, otherwise it won't run.

Press the **up arrow** to retrieve the `node first_lab.js` command. That way, you don't have to type it each time to run the file.

<br>
<hr>

# Errors

Cut and paste the following code into your text editor (the "Cheers" song lyrics). The code is broken -- there are **three errors**. You might already see the errors, but --

Run the code and read the error message in the terminal. Using information from the error message (line numbers, etc.), debug the code and make it work.

At the same time, write a comment below the code that specifies what _type_ of error it was. Example, if you get this:

![](https://i.imgur.com/KRHtmPM.png)

Write

```
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

# Boolean Expressions
**... and arithmetic**

By just looking at the following expressions, determine in your mind whether or not each will evaluate to **true** or **false**

1. `999 > 999`
=> false
2. `999 == 999`
=> true
3. `999 != 999`
=> false
4. `-5 >= -4`
=> false
5. `100 <= -100`
=> false
6. `20 + 5 < 5`
=> false
7. `81 / 9 == 9`
=> true
8. `9 != 8 + 1`
=> false

<br>
<hr>

# Assignment operator vs Equality operator

What is the difference between:

the **assignment operator** `=`

and the **equality operator** `==`

?

```
My Answer: The assigment operator is used to assign a value to a variable, while the equality operator is used to check whether or not two values, variables, or equations are equal in value.
```

<br>
<hr>

# While Loops: reps and reps

## 1

Write a *while* loop that will log in the console

```
'Ginger chocolate honey patties'
```

1000 times. You can test it out with a smaller number first, such as 10, and when that works, use 1000.

Make sure you do not run an infinite loop! If you do, close your Terminal. Oops!
```
let i = 0;
while (i <= 1000) {
  console.log("Ginger chocolate honey patties");
  i++;
};
```

## 2

Write another *while* loop that counts from 0 to 1000 and will log in the console the current loop number.

> => 0
>
> => 1
>
> => 2
>
> => 3

etc.

```
let i = 0;
while (i <= 1000) {
  console.log(i);
  i++;
};
```

## 3

Write another *while* loop that prints a message to the console _and_ interpolates the current loop number. Make it count from 0 to 1000.

> => "Current loop number is: 0"
>
> => "Current loop number is: 1"
>
> => "Current loop number is: 2"
>
> => "Current loop number is: 3"

```
let i = 0;
while (i <= 1000) {
  console.log("Current loop number is: " + i);
  i++;
};
```
<br>

**NOTE:** You should not need to see the 'correct answers' in this markdown for these loops. Either they work, or they don't. **Test** them thoroughly to make sure they are giving you the desired output.

<br>
<hr>

# For loops

# 1
* Write a **for loop** that counts from 0 to 100 and console.logs each number.

```
for (i = 0; i <= 100; i++) {
  console.log(i);
};
```
# 2
* Write another **for loop** that counts from 7 to 635 (no more, no less!), and console.logs each number.

```
for (i = 7; i <= 635; i++) {
  console.log(i);
};
```

# 3
* Declare a variable `let start = 0`
* Declare a variable `const limit = 100`
* Write a for loop that counts from the value of `start` to the value of `limit`, using those variables in the **control panel** of the loop.

Test the loop thoroughly.

```
let start = 0;
const limit = 100;
for (i = start; i <= limit; i++) {
  console.log(i);
};
```
# 4
* Think of something in real life, or nature, or wherever / whenever that displays **looping** behavior.

Use a **for loop** to model the looping behavior of that thing.

Where does the loop begin? Where should it end? Does it simply count from one number to another? Or does it change or mutate data?

<br>
<hr>

# Conclusion

Congrats! There is no need to submit this lab. You will be receiving homework for tonight soon.

If you want more to do, tomorrow we will be getting into git and Github. Use your **research skills** (Google-fu) to find out more about:

* The difference between git and github
```
Git is a revision control system, a tool to manage your source code history, while github is a hosting service for Git repositories.
```
* What is a Github repo
```
A directory or storage space on Github where your project lives.
```
* forking a repo on Github
```
Forking a repository means making a copy of the repo, this allows you to freely experiment with changes without affecting the original project.
```
* cloning a repo from Github
```
Cloning a repository means that you download the whole code of the repository onto your local machine through the command line using the command "git clone".
```
* What does `git push origin master` do?
* What would `git pull upstream master` do?

<br>
<hr>
