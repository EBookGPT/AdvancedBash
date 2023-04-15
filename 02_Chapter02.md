# Chapter 2: Shell Variables and Environment in Advanced Bash

Oh, the variables we'll see, 
In this chapter about Shell Variables and Environment, 
We'll learn what they are, 
How they work, 
And why they're important to the shell's mirth.

Variables hold values and data, 
And they're used to reference data later, 
They make it easier to write Bash, 
So our commands can run much greater.

Environment variables are quite neat, 
They help with running programs and scripts,
And we can view their contents too, 
By using the `printenv` trick.

But wait, there's more to this tale, 
We can create our own variables, without fail,
The `declare` command sets types, 
And helps us reference them with gripes.

For example, `declare -i` sets an integer variable with ease, 
Or `declare -a` sets an array with peace,
"declare" is our friend, 
And can help our scripts to no end.

So let's dive in and see, 
The wonders of Shell Variables and Environment in this spree,
With Bash code and good cheer, 
We'll master these concepts with no fear!
# Alice in the World of Bash

Alice had fallen into a rabbit hole, 
But this time it was different, 
She fell into a world of Bash, 
Where variables were always imminent.

The Mad Hatter greeted her with a smile, 
And showed her a world of variables galore, 
"Shell variables and Environment are important to know, 
For they will help you explore!"

Alice looked around in wonder, 
As variables danced around like thunder, 
The Hatter showed her a `printenv`, 
And the contents of the variables were sent to ascend.

"Environment variables are important," he said with a grin, 
"For without them, scripts would be a spin," 
Alice nodded in agreement, 
As variables swirled in contentment.

But what about creating new variables, 
And setting their values for all to see, 
The Hatter showed her the path of `declare`, 
And Alice was filled with glee.

"Declare -i sets an integer," he said, 
"And `declare -a` sets an array instead," 
Alice was like a sponge, absorbing it all, 
As variables cascaded like a waterfall.

The Cheshire Cat appeared, smiling wide, 
"What about `readonly`?" he said with pride, 
The Hatter explained it with ease, 
As Alice listened in a state of please.

By the end of her adventure, 
Alice was a variable master, 
She manipulated values with grace and ease, 
And could declare with a sneeze.

"Thank you, Hatter," Alice exclaimed, 
"For showing me the world of Bash with no restrain," 
And as she left the crazy world of Bash, 
Alice knew that variables would always last.
# The Code Behind the Story

In the Alice in Wonderland trippy story, variables play a major role. Here is an explanation of the Bash code used to illustrate the concepts of the story:

## `printenv`

`printenv` is a Bash command used to print the values of environment variables. The Mad Hatter shows Alice this command to help her understand the importance of environment variables in running programs and scripts.

```bash
printenv
```

## `declare`

`declare` is a Bash built-in command used to set attributes for variables. In the story, the Mad Hatter shows Alice the various types of attributes that can be set with `declare`, including `-i` for integers and `-a` for arrays.

```bash
declare -i var=10    # set an integer variable
declare -a arr=(1 2 3)   # create an array variable
```

## `readonly`

`readonly` is a Bash keyword used to create variables that cannot be changed or unset later. The Cheshire Cat shows Alice this command to illustrate the importance of data protection.

```bash
readonly var="hello"    # set a read-only variable
```

By understanding these Bash commands and the concept of variables in Bash, you too can become a variable master like Alice!


[Next Chapter](03_Chapter03.md)