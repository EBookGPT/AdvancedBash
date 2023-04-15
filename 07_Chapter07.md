# Chapter 7: Conditional Statements

Welcome back dear reader, to yet another fascinating chapter on Advanced Bash! In the previous chapter, we delved into the world of Arrays and Strings. We hope you enjoyed learning about all the ways you can manipulate these complex data types.

In this chapter, we are lucky to have a special guest, Steve Parker! Steve is a renowned expert in Unix/Linux programming and system administration, and has authored several books on the subject.

Together, we will explore the world of Conditional Statements in Bash, and you will learn how to use them to make decisions and control the flow of your scripts. 

## The Need for Conditional Statements

Have you ever wondered how programs make decisions? Perhaps you have encountered a situation where the program needed to perform an action based on some input or data? This is where Conditional Statements come in handy. 

A Conditional Statement is a statement that performs an action based on whether a particular condition is true or false. Advanced Bash provides several different Conditional Statements that can be used to control the flow of your script, and make decisions based on user input, system output, or other factors.

## If Statements

One of the most commonly used Conditional Statements in Advanced Bash is the `if` statement. The `if` statement allows you to check whether a certain condition is true or false, and perform a particular action based on the result.

Here's an example of how an `if` statement works:

```bash
if [ $var -gt 10 ]
then
  echo "The variable is greater than 10"
fi
```

In this example, the script checks the value of the variable `var`. If the value is greater than 10, it prints "The variable is greater than 10" to the console. 

## Else and Elif Statements

In some cases, you may want to perform a different action if the condition in the `if` statement is false. This is where the `else` statement comes in. 

Here's how an `if-else` statement works:

```bash
if [ $var -gt 10 ]
then
  echo "The variable is greater than 10"
else
  echo "The variable is less than or equal to 10"
fi
```

In this example, if the value of `var` is greater than 10, the script prints "The variable is greater than 10" to the console. Otherwise, it prints "The variable is less than or equal to 10".

In some cases, you may have multiple conditions to check. For this, you can use the `elif` statement. 

Here's an example of how an `if-elif-else` statement works:

```bash
if [ $var -gt 10 ]
then
  echo "The variable is greater than 10"
elif [ $var -eq 10 ] 
then
  echo "The variable is equal to 10"
else
  echo "The variable is less than 10"
fi
```

In this example, if the value of `var` is greater than 10, the script prints "The variable is greater than 10" to the console. If the value is equal to 10, it prints "The variable is equal to 10". Otherwise, it prints "The variable is less than 10".

## Conclusion

And there you have it, dear reader! In this chapter, we explored the world of Conditional Statements in Bash, and learned how to use them to make decisions and control the flow of our scripts.

We hope you enjoyed reading this chapter, and don't forget to practice your coding skills! Remember, coding is like a muscle, the more you exercise it, the stronger it gets.

Thank you for joining us on this journey, and don't forget to check out Steve Parker's books on Unix/Linux programming and system administration!
# Chapter 7: Conditional Statements - A Trippy Adventure in Wonderland

Once upon a time, Alice found herself in a strange world called Wonderland. As she wandered around this strange land, she came across a group of talking animals who were all gathered around a box.

"What's in the box?" asked Alice, intrigued.

"The box contains a code that will help us control the flow of our scripts," replied a wise old owl named Steve Parker.

"Control the flow of your scripts?" asked Alice, puzzled.

"Yes, dear Alice," said Steve. "In Advanced Bash, we use Conditional Statements to make decisions and control the flow of our scripts."

"Conditional Statements?" repeated Alice, still confused.

"Yes, conditional statements," replied Steve. "They check whether a certain condition is true or false, and then perform a particular action based on the result. Let me show you an example!"

And with a snap of his fingers, the box opened and out flew a flock of birds.

"If the value of `x` is greater than 10, then we will make the birds fly," said Steve.

"Fly? How exciting!" exclaimed Alice.

Steve then began to type a magic spell using Advanced Bash:

```bash
if [ $x -gt 10 ]
then
  echo "Fly, my birds, fly!"
fi
```

As soon as Steve hit enter, the birds began to soar into the sky. Alice watched in amazement as they circled around her head.

"This is incredible!" she cried.

"But wait, there's more," said Steve, with a twinkle in his eye.

And with another snap of his fingers, the sky turned dark and stormy. Lightning flashed, and Alice felt a cold wind blowing.

"If `y` is less than 5, we will create a storm," said Steve.

Alice watched as Steve continued typing:

```bash
if [ $y -lt 5 ]
then
  echo "Let the storm rage!"
else
  echo "The weather is calm."
fi
```

And just like that, the storm disappeared, and the sun came out. Alice was impressed - she had learned so much about controlling the flow of scripts!

"Well done, Alice!" said Steve. "You have learned the power of Conditional Statements in Advanced Bash."

As Alice said her goodbyes and prepared to leave Wonderland, she couldn't help but feel grateful for Steve's help and guidance. She walked away feeling confident and empowered, ready to use Advanced Bash to create magic of her own.
## Explanation of the Code

In the Alice in Wonderland trippy story, we saw how Steve Parker used Conditional Statements to control the flow of scripts in Advanced Bash. Let's take a closer look at the code he used to make his creations come to life!

### If Statement

The first example Steve showed us was an if statement. Here's the code he used:

```bash
if [ $x -gt 10 ]
then
  echo "Fly, my birds, fly!"
fi
```

This code checks whether the value of the variable `$x` is greater than 10. If the condition is true, then the script prints "Fly, my birds, fly!" to the console.

Notice how the `if` statement is followed by the condition to check (`[ $x -gt 10 ]`), and then the keyword `then`. If the condition is true, then the code within the `if` statement will be executed.

### If-Else Statement

The second example Steve showed Alice was an if-else statement. Here's the code he used:

```bash
if [ $y -lt 5 ]
then
  echo "Let the storm rage!"
else
  echo "The weather is calm."
fi
```

This code checks whether the value of the variable `$y` is less than 5. If the condition is true, then the script prints "Let the storm rage!" to the console. If the condition is false, then the script prints "The weather is calm.".

Notice that the `if` statement is followed by the condition to check (`[ $y -lt 5 ]`), and the keyword `then`. If the condition is true, the code within the `if` block will be executed. Otherwise, the code within the `else` block will be executed.

### Elif Statement

Finally, Steve showed Alice an example of an if-elif-else statement. Here's the code he used:

```bash
if [ $var -gt 10 ]
then
  echo "The variable is greater than 10"
elif [ $var -eq 10 ] 
then
  echo "The variable is equal to 10"
else
  echo "The variable is less than 10"
fi
```

In this code, we check the value of the variable `$var`. If the value is greater than 10, the script prints "The variable is greater than 10" to the console. If the value is equal to 10, then the script prints "The variable is equal to 10". If the value is less than 10, then the script prints "The variable is less than 10".

Notice how we use the `elif` keyword to add another condition to check if the previous condition was false. If both conditions are false, then the code within the `else` block will be executed.

## Conclusion

In this chapter about Conditional Statements in Advanced Bash, we have explored the power of these statements and how they can be used to make decisions and control the flow of scripts. From if statements to elif statements and if-else statements, we have seen how these constructs can be used to create exciting and dynamic scripts. We hope you have enjoyed learning about them and that you put them to good use in your Bash programming endeavors!


[Next Chapter](08_Chapter08.md)