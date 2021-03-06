---
title: The Design Recipe
view: page_curriculum
theme: none
---


<%= partial('curriculum_header', :unplugged=>true, :title=> 'The Design Recpie',:disclaimer=>'Basic lesson time includes activity only. Introductory and Wrap-Up suggestions can be used to delve deeper when time allows.', :time=>25) %>

[content]

[together]

## Lesson Overview
The Design Recipe is a structured approach to writing functions that solve world problems.

[summary]

## Teaching Summary
### **Getting Started**
 
1) [Vocabulary](#Vocab)
2) [What is the Design Recipe](#GetStarted)  

### **Activity: The Design Recipe**  

3) [Collaborative Design](#Activity1)   

### **Assessment**
6) [Design Recipe Assessment](#Assessment)

[/summary]

## Lesson Objectives 
### Students will:
- Use the Design Recipe to define functions to solve word problems

[/together]

[together]

# Teaching Guide
[/together]

[together]

## Getting Started


### <a name="Vocab"></a> 1) Vocabulary
This lesson has two new and important words:<br/>

- **Design Recipe** - a sequence of steps to document, test, and write functions
- **Purpose Statement** - a brief description of what the function does

### <a name="GetStarted"></a> 2) What is the Design Recipe

The Design Recipe is a roadmap for defining functions, which programmers use to make sure the code they write does what they want it to do. Each step builds on the last, so any mistakes can be caught early in the process. This roadmap has a series of steps:

1. Write a Contract that describes the word problem
2. Write Examples based on the contract
3. Define a function that matches the examples

Let's start out by applying the Design Recipe together to the following problems:

- Define a function ’purple-star’, that takes in the size of the star and produces an outlined, purple star of the given size.
- Define a function ’spot’, that takes in a color and produces a solid circle of radius 50, filled in with that color
- To find the average of two numbers, they should be added together and divided by two. Define a function ’average’, which takes in two numbers and produces their average
- A company logo is a word drawn in big, red letters, rotated some number of degrees. Define a function ’logo’, that takes in a company name and a rotation, and produces a logo for that company

Be sure to include a good Name for each function, and remember that the Domain and Range can only include types like Numbers, Images, Strings, etc.

A Contract is the foundation for a function, which gives programmers just enough information to use them: the name of the function, the types of data it expects and the type of data it returns.
Now that you’ve completed the Contracts for all four word problems, try to generate two Examples for each one.

Challenge students to defend their Examples (their function name, the number of inputs, their types and the type of the returned value). Make sure that the two Examples for each function have different input values! For each of these questions, students must be able to point to the specific part of their Contract as the justification for their Example.

Once you have two or more Examples, it should be easy to identify what has changed between them. In fact, the number of things that change should match the number of things in the function’s Domain: if the Domain has a Number and a String in it, then those two values should be the things that differ between your Examples.

Identify what has changed between these Examples, and use this information to define all four functions.

Make sure students have chosen good variable names for their function definitions, and ask students to justify every part of the function body. The only acceptable answers should be "I copied this because it’s the same in both Examples", or "I used a variable name because it differs between Examples."

Circle the Name of the function, and underline what it takes in and what it produces.

Write the Contract for this function, using what you underlined to help you find the Domain and Range.

Underneath the Contract, write the Purpose Statement by summarizing what the function does in a single sentence

Challenge students to explain why this function does not need to know the color of the square, or whether or not it is solid. They main idea here is that the function already "knows" these things, so the only thing that is changing is the size of the square. Note that there are actually two easy solutions here: using the square function, or using rectangle with the same variable for width and height.

Remember that the Contract and Purpose Statement can be used to write the Examples, even if a programmer isn’t sure how to begin.

Using only the Contract and Purpose Statement, see if you can answer the following questions:
Every Example begins with the name of the function. Where could you find the name of the function?

Every Example has to include sample inputs. Where could you find out how many inputs this function needs, and what types they are?

Every Example has to include an expression for what the function should do when given an input. Where could you look to find out what this function does?

Write two Examples on your paper, then circle and label what is changing between them.

Make sure students realize that every answer can be found in the Contract or Purpose Statement. Suggestion: write these steps on the board, and draw arrows between them to highlight the process. The goal here is to get students into the habit of asking themselves these questions each time they write Examples, and then using their own work from the previous step to find the answers. NOTE: students can solve this using either square or rectangle. The latter requires them to use the same variable twice, which is a useful thought-exercise.

Once the two Examples are written and the variable (or variables) are labeled, it becomes easy to define the function.

Using the Contract, Purpose Statement and Examples, see if you can answer the following questions:

Every function definition begins with the name. Where did you write this already?

Every definition has to include variable names for the inputs. Where did you write these down?

Every definition should work exactly the way the Examples did. Where could you look to figure out what the function should do?

Write the function definition on your paper.

[/together]

[together]

## Activities:
### <a name="Activity1"></a> 3) Collaborative Design

Put students into groups of 3 - each member of the group will represent one step of the Design Recipe

1. Contract
2. Examples
3. Function

Each group will work through the word problems on the [Design Recipe Worksheet](needadesignrecipeworksheet.pdf). Each group member should stay true to their role and make sure to complete the steps in the right order.

[/together]

[together]

## Assessment 
### <a name="Assessment"></a>4) The Design Recipe Assessment

Visit [MSM Stage 8](http://studio.code.org/s/msm/stage/8/puzzle/1) in Code Studio to complete the assessments.

[/together]

[standards]

## Connections and Background Information




[/standards]

[/content]

<link rel="stylesheet" type="text/css" href="../docs/morestyle.css"/>
