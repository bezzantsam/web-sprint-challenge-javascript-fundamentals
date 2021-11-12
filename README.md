# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge.

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results

### Commits

Set up codegrade early and commit your code regularly and meaningfully.

## Interview Questions

### (please edit this file and write your answer below each question.)

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each.

.map function populates a new array with the results of an array and a callback function iterating through every index of an original non mutating array. This method has a mind blowing amount of potential use cases and that explains its prominence. It could be useful for taking a data set and applying a function to model, interpret or compute that data into a new data set in an array. Say for example a retailer wanted to organize a data set of stores into an array of most profitable after taxes and expenses.

.reduce uses user directed function to cumulatively operate on a data set and return a conglomerated result. A potential use case for this function would be gros profit tally for a casino or business, a running total of customers or visitors at a site or store and I see many potential database applications.

.filter Invokes a callback function once on every index of an array. It is a test returning a boolean result and organizing the items that pass this test into a new array. The first example I could think of was the CCAT test I took to get into Lambda and how I was accepted right after. My score I imagine was compared to a benchmark and found to be >= a minimum score and the boolean showed true and I was pushed into an array of new students.

2. Explain the difference between a callback and a higher order function.
   A higher order function receives other functions as arguments. A callback function is that very function being passed as an argument.

3. Explain what a closure is.
   A closure is when a function reaches outside of itself for a variable in another function or scope.

4. Describe the four principles of the 'this' keyword.
   1.) global binding: when the value of "this" is window scoped

   2.) implicit binding: when the function is called by a preceding . the object left of the dot is "this"

   3.) new binding: when a constructor function is used "this" refers to the specific instantiation of that object created by constructor function.

   4.) explicit binding: whenever a call or apply method is used "this is explicitly defined

5. Why do we need super() in an extended class?

   super() calls a parent objects constructor method and makes properties. It extends Javascripts prototypal inheritence model and makes it more like classes in an object oriented language.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade.

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:

1. Fork the repo
2. Go into canvas and connect your reop to codegrade
3. Clone your forked version of the repo
4. DO NOT CREATE A BRANCH. You will be pushing your changes to the main/master today
5. cd into your repo
6. open the terminal in your vs code and type `npm install`
7. next type `npm run test` in your terminal
8. Complete your work making regular commits to main/ master your codegrade score will update each time you make a push.

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start`
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources

[Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://lambdaschool.notion.site/lambdaschool/Lambda-School-Git-Flow-Step-by-step-269f68ae3bf64eb689a8328715a179f9) See part 2, submitting an assignment with codegrade
