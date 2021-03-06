## Homework week 1:

>[Here](https://github.com/HackYourFuture/JavaScript/tree/master/Week1/README.md) you find the readings you have to complete before the second lecture.

We covered a bit of command line usage in the first class and got a program running which is great. If you need a refresher for the command line please have a look here: https://github.com/SocialHackersCodeSchool/CommandLine

## Before you start with the homework:

1. Watch: [What is programming](https://www.khanacademy.org/computing/computer-programming/programming/intro-to-programming/v/programming-intro) Just watch the 2 min video, you do not have to do the entire JavaScript course (It could be useful later on though). 

## Step 1: Command Line

1. Create a `.js` file that prints `Hello` when you run it from the command line. (Hint: `node` is the program that can run your JavaScript files.)

```
Write commands to do following:
1. create a directory. Enter a directory. Create an empty file named blank. 
    2. Then write the content `"Hello"` five times to the file greetings.txt. 
   Then copy the file greetings.txt and paste its contents into 1.txt, 2.txt, 3.txt, 4.txt and 5.txt.
    3. Then write the text "cat" to pets.txt
   Then append the text "dog" to pets.txt
   Then append the text "hamster" to pets.txt
    4. Then write the text "cat" to commands.txt
   Then append the text "ls" to commands.txt
   Then append the text "pwd" to commands.txt
    5. Then find unique strings from these two files pets.txt and commands.txt
   and store the unique strings in lovelyCommands.txt
```


## Step 2: JavaScript

> For all the following exercises create a new .js file. Try to find a proper name for each file or make a small comment about what it does inside for future reference

1. Declare a variable `x` and initialize it with an integer.

2. How do you round the number 7.25, to the nearest integer?

    currnum = 5.49999999999999955 ;

    if (currnum % 1 >= 0.5) {

      console.log (currnum - currnum % 1 + 1) ;
    }
    else {

      console.log (currnum - currnum % 1) ;
    }

3. Create a array called `colors` with the strings red, green and blue inside.

4. How can you find the length of the string you just created?

5. Write a program that checks the types of two variables and prints out `SAME TYPE` if they are the same type. 
For example: 
    ```js
    let x = 9;
    let y = 'Hello';

    if () {
      console.log('SAME TYPE');
    }

    ```

6. If `x` equals 7, and the only other statement is `x = x % 3`, what would be the new value of `x`?

   let x = 7 ;
   x = x % 3 ;
   console.log (x) ;
   1

7. Write a program to answer the following questions:
* Can you store multiple types in an array? Numbers and strings?
* Can you compare inifities? (Not in Eyad's world) - does 6/0 == 10/0? How can you test this?

  6 / 0 == -6 / -0 == Infinity == Number.POSITIVE_INFINITY
  -6 / 0 == 6 / -0 == -6 / 0 == Number.NEGATIVE_INFINITY

### Step 3: **Some freeCodeCamp challenges (10 hours):**

On freeCodeCamp.com please do the [Basic JavaScript](https://www.freecodecamp.com/challenges/learn-how-free-code-camp-works) exercises up and until the __"Shopping List"__ exercise (there are some topics we did not cover but you can do it).

### How to hand in Homework:
```
steps:
• Create a Github account
• Create a new repository (name it something like sha-javascript1) make sure you select the option: initialize with README
• inside this repository create a folder "week1"
• Upload the files you created on your computer inside the week1 folder, write a description for this “commit”
• Open the file in your README to check if this all worked

• Create a new repository "sha-javascript1". Also create a new folder "week1" inside this repository. 
• Upload your homework files inside the week1 folder and write a description for this “commit”.
• Your sha-javascript1/week1 should now contain all your homework files.
```

### Hint
If you solve the FreeCodeCamp challenges and they are new concepts to you and you would like to take a look at them later on in the program, Copy your answers from FCC in a .js file and upload them to Github in a repository for future reference. In this way you build your own little documentation, if you look back at them first try to understand what it does before you run them.

:star: Additional resources and review: [here](https://github.com/SocialHackersCodeSchool/JavaScript/tree/master/Week1/REVIEW.md) (work in progress):star:

