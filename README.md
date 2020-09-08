# JetBrains_Academy


# Stage 1/5: Hello! What’s your name?

## Description

Digital personal assistants help people to drive cars, plan their day, buy something online. In a sense, they are simplified versions of artificial intelligence with whom you can talk.

In this project, you will develop step by step a simple bot that will help you study programming.

## Objective

For the first stage, you will write a bot who displays a greeting, its name and the date of its creation. First impressions count!

Your program should print the following lines:

    Hello! My name is {botName}.
    I was created in {birthYear}.

Instead of  {botName}  print any name you choose and replace  {birthYear}  with the current year (four digits).

## Example

Output:

    Hello! My name is Aid.
    I was created in 2020.

You can change the text if you want but print exactly two lines.

Next, we will use  **Aid**  and  **2020**  as your bot's name and its birth year, but you can change it if you need to.



# Stage 2/5: What's my name?

## Description

The greeting part is great, but chatbots are also supposed to interact with a user. It's time to implement this functionality.

## Objective

At this stage, you will introduce yourself to the bot so that it can greet you by your name.

Your program should print the following lines:

    Hello! My name is Aid.
    I was created in 2020.
    Please, remind me your name.
    What a great name you have, {yourName}!

You may change the name and the creation year of your bot if you want.

Instead of  {yourName}, the bot must print your name entered from the standard input.

## Example

The greater-than symbol followed by space (> ) represents the user input. Notice that it's not the part of the input.

**Example 1:**  _a dialogue with the bot_

    Hello! My name is Aid.
    I was created in 2020.
    Please, remind me your name.
    > Max
    What a great name you have, Max!

Use the provided template to simplify your work. You can change the text, but not the number of printed lines.


# Stage 3/5: How old are you?

## Description

Keep improving your bot by developing new skills for it. We suggest a simple guessing game that will predict the age of a user.

It's based on a simple math trick. First, take a look at this formula:

    age = (remainder3 * 70 + remainder5 * 21 + remainder7 * 15) % 105

The numbersremainder3,  remainder5  and  remainder7  are the remainders of division by 3, 5 and 7 respectively.

It turns out that for each number ranging from  _0_  to  _104_  the calculation will result in the number itself. This perfectly fits the ordinary age range, doesn't it? Ask a user for the remainders and use them to guess the age!

## Objective

At this stage, you will introduce yourself to the bot. It will greet you by your name and then try to guess your age using arithmetic operations.

Your program should print the following lines:

    Hello! My name is Aid.
    I was created in 2020.
    Please, remind me your name.
    What a great name you have, Max!
    Let me guess your age.
    Enter remainders of dividing your age by 3, 5 and 7.
    Your age is {yourAge}; that's a good time to start programming!

Read three numbers from the standard input. Assume that all the numbers will be given on separate lines.

Instead of  {yourAge}, the bot will print the age determined according to the special formula discussed above.

## Example

The greater-than symbol followed by space (> ) represents the user input. Notice that it's not the part of the input.

**Example 1:**  _a dialogue with the bot_

    Hello! My name is Aid.
    I was created in 2020.
    Please, remind me your name.
    > Max
    What a great name you have, Max!
    Let me guess your age.
    Enter remainders of dividing your age by 3, 5 and 7.
    > 1
    > 2
    > 1
    Your age is 22; that's a good time to start programming!

Use the provided template to simplify your work. You can change the text, but not the number of printed lines.

Stage 4/5: Let’s count!
Description
Now you will teach your bot to count. It's going to become an expert in numbers!

Objective
At this stage, you will program the bot to count from 0 to any positive number users enter.

Example
The greater-than symbol followed by space (> ) represents the user input. Notice that it's not the part of the input.

Example 1: a dialogue with the new version of the bot

    Hello! My name is Aid.
    I was created in 2020.
    Please, remind me your name.
    > Max
    What a great name you have, Max!
    Let me guess your age.
    Say me remainders of dividing your age by 3, 5 and 7.
    > 1
    > 2
    > 1
    Your age is 22; that's a good time to start programming!
    Now I will prove to you that I can count to any number you want.
    > 5
    0!
    1!
    2!
    3!
    4!
    5!
    Completed, have a nice day!
Note: each number starts with a new line, and after a number, the bot should print the exclamation mark.

Use the provided template to simplify your work. You can change the text if you want, but be especially careful when counting numbers.


# Stage 5/5: The student and the teacher

## Description

At the final stage, you will improve your simple bot so that it can give you a test and check your answers. The test should be a multiple-choice quiz about programming. Your bot has to repeat the test until you answer correctly and congratulate you upon completion.

## Objective

Your bot can ask anything you want, but there are two rules for your output:

-   the line with the test should end with the question mark character;
-   an option starts with a digit followed by the dot (1.,  2.,  3.,  4.)

If a user enters an incorrect answer, the bot may print a message:

Please, try again.

The program should stop on the correct answer and print  **Congratulations, have a nice day!** at the end.

## Example

The greater-than symbol followed by space (> ) represents the user input. Notice that it's not the part of the input.

**Example 1:**  _a dialogue with the final version of your bot_

Hello! My name is Aid.
I was created in 2020.
Please, remind me your name.

    > Max
    What a great name you have, Max!
    Let me guess your age.
    Enter remainders of dividing your age by 3, 5 and 7.
    > 1
    > 2
    > 1
    Your age is 22: that's a good time to start programming!
    Now I will prove to you that I can count to any number you want.
    > 3
    0!
    1!
    2!
    3!
    Let's test your programming knowledge.
    Why do we use methods?
    1. To repeat a statement multiple times.
    2. To decompose a program into several small subroutines.
    3. To determine the execution time of a program.
    4. To interrupt the execution of a program.
    > 4
    Please, try again.
    > 2
    Congratulations, have a nice day!

The program must end with the  **Congratulations, have a nice day!**  message.

Use the provided template to simplify your work. You can change the text if you want. Please note that we use functions to make it easy to understand the program and add new code to it or edit later.

<<<<<<< HEAD
>>>>>>> 173a62e7b9c7a10574a547f4742fe1ff0e5c6869
