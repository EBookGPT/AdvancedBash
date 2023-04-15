# Chapter 8: Loops and Iterations in the World of Bash

Welcome back, my friend, to the world of Bash,  
Where the magic of coding continues in a flash.  
Last chapter we learned of conditions and more,  
Where we made Bash do things like never before.  

Now let’s take a journey and go for a ride,  
Through the world of loops and iterations side by side.  
The power they give you is nothing but grand,  
Complex tasks can be done with just a few commands.  

You may ask, what is a loop, what does it do?  
It’s a way to run commands, not just one or two.  
With iterations, we can repeat without end,  
Or until a certain condition, we can bend.  

It’s time to explore the three types of loops we will meet,  
For, while, and until, each unique, no deception, so sweet.  
We’ll learn when to use each, how to break or continue,  
And at the end, we’ll be coding like an advanced menu.  

So buckle up Alice, it's time to push through,  
As we journey through Bash, with a command or two.  
Join me in this trippy wonderland of code,  
Where loops will make everything come alive and explode!
# The Trippy World of Loops and Iterations in Bash

Alice fell deep into Bash,  
Where she found herself in a code-filled crash.  
As she looked around, she saw loops in sight,  
For, while, and until, shining so bright.  

She followed the trail of curly braces,  
And found a rabbit hole, in multiple places.  
Each hole led to a different iteration,  
And she marveled at this Bash creation.  

The first hole led to a for-loop land,  
Where she met a Mad Hatter, so grand.  
Ever so merry, he greeted her with a smile,  
Saying "For-loops will save you lots of trial."  

With this, he taught her how to iterate,  
Through a series of tasks, at a steady rate.  
From a list of numbers to files in a folder,  
A for-loop made iteration so much bolder.  

The second hole took her to a while-loop scene,  
Where a Caterpillar sat, looking serene.  
"Ah, while-loops, a powerful feature," she said,  
"As they repeat until a condition is dead."  

With a flick of his hookah, he showed her the way,  
To iterate through code, until a point of delay.  
From user input to array elements,  
A while-loop made it a perfect exponent.  

The third hole opened into an until-loop stage,  
Where the Cheshire Cat sat, in a peaceful engage.  
"Until-loops are fun, a way to reverse," she began,  
"And repeat until a condition ends as bland."  

With a smirk and a wave, she showed Alice the task,  
Of iterating until a condition unmasked.  
From a file search to a ping address,  
An until-loop made it such a true success.  

As Alice went through the loops, she saw a pattern,  
Of how iteration solved problems, and how it shouldn't be scattered.  
She learned when to use for, while, or until,  
And made her Bash coding, effortlessly still.  

With a big smile on her face, Alice said her farewell,  
To the Mad Hatter, the Caterpillar, and the Cheshire Cat as well.  
For she now had the power of loops and iterations,  
To conquer Bash coding with no frustration.  

So dear friends, as you exit Bash land,  
Remember to use loops with a steady hand.  
For iteration is a powerful tool,  
In the Alice in Wonderland world of Bash, where everything is cool!
# Decoding the Bash Magic of Loops and Iterations

Now that we've journeyed through the trippy world of loops and iterations in Bash, it's time to take a closer look at the code used to make it all happen.

First and foremost, it's important to understand the basic syntax of each loop:

## For-Loop
```
for variable_name in list
do
  # commands to execute 
done
```
A for-loop is used to iterate through a list of items, performing a set of commands on each item. The variable_name can be any name you choose and is used to represent each item in the list. The list can be a series of numbers, filenames, or any other group of items. The commands to execute go in between the `do` and `done` statements.

## While-Loop
```
while [ condition ]
do
  # commands to execute
done
```
A while-loop is used to repeatedly execute a set of commands, as long as a specific condition is true. The condition can be checking for a file or user input, and the commands to execute go in between the `do` and `done` statements.

## Until-Loop
```
until [ condition ]
do
  # commands to execute
done
```
An until-loop is similar to a while-loop, in that it repeatedly executes a set of commands. However, it continues to execute the commands until a specific condition is true. The commands to execute go in between the `do` and `done` statements.

Now, let's take a look at some examples of loops in action:

## For-Loop Example
```
for num in {1..10}
do
  echo $num
done
```
This code will iterate through the numbers 1 to 10 and print each number to the terminal.

## While-Loop Example
```
while [ ! -f myfile.txt ]
do
  sleep 1
done
```
This code will keep checking if `myfile.txt` exists until it appears. The `sleep 1` command is used to pause the script for 1 second between each check.

## Until-Loop Example
```
until [ $(ping -c 1 google.com > /dev/null 2>&1; echo $?) -eq 0 ]
do
  echo "Waiting for internet connection..."
  sleep 1
done
```
This code will keep pinging `google.com` until a successful connection is made. The `sleep 1` command is used to pause the script for 1 second between each ping.

These are just a few examples of the power of loops and iterations in Bash. The possibilities are endless, and it's up to you to get creative with your code!


[Next Chapter](09_Chapter09.md)