# exercise-fundamental-javascript-with-fluffy

## Learning Goals

Upon completing this exercise, you will be able to:

- Declare variables in JavaScript
- Effectively use string concatenation and template literals
- Understand various primitive data types (numbers, strings and booleans)
- Use comparison and logical operators to create conditional statements
- Write and execute if-else statements to control program flow
- Create for loops to repeat code execution
- Use do..while loops for condition based iteration
- Gain confidence in writing and understanding basic JavaScript algorithms

## Introduction

Welcome to your first JavaScript coding exercise! 🎉

Now that we've dipped our toes into the world of JavaScript, it's time to put your newly acquired skills to the test. This exercise is designed to help you practice and reinforce the fundamental concepts we've covered so far.

In this exercise, we'll be working with our furry friend Fluffy, a lovable & energetic dog.

Through Fluffy's daily adventures, we'll explore various JavaScript concepts including:

- Variables and primitive data types
- Basic operators
- Conditional statements (if-else)
- Loops (for, while, do-while)

Remember, coding is a skill that improves with practice. Don't worry if you find some tasks challenging at first – that's all part of the learning process! Feel free to refer back to the lessons, or ask for help if you get stuck.

Are you ready to help Fluffy navigate through his day using JavaScript? 
Let's dive in and start coding! 👨🏻‍💻

## Getting Started

Follow these steps to begin to begin your development journey:

1. Fork the repo.
2. Clone the Repository to your Computer
3. Open the Repository in VS Code
4. Start the Live Server in VS Code
5. Follow the instructions below

## Instructions

Alright, future JavaScript wizards! 🧙🏻‍♂️ 

Open up the `index.js` file.

Inside, you'll see comments in the file that look like this:  `// Task 1: ....` 
This is where you should write your JavaScript solutions.

Fire up the Live Server in VS Code to see your code in action. 

Don’t forget to read each task carefully as sometimes, fluffy’s adventures have very specific requirements!

Complete the following tasks to complete this exercise:

### Task 1: Variables

1. There's a beautiful Golden Retriever walking around but we have no idea what it's called... Create a variable `dog` which we can update later, if we ever find out the name.
Use `let` for this variable.
2. The dog is called Fluffy! Update `dog` to reflect this.
3. Fluffy just turned double figures! Create a new variable `age` to reflect this. 
Use `let` for this variable as well.
4. Print the following to the console using a *template literal*:   
“I can’t believe that Fluffy just turned 10 years old!”
5. We've just learnt that Fluffy's breed will never change. 
Create a constant `breed` and set it to "Golden Retriever".
6. Oops, looks like they miscalculated and got the age wrong! 
Fluffy is actually 11 years old. Update Fluffy’s `age`
7. Print a new message to the console using all three variables:
"Fluffy is an 11-year-old Golden Retriever.

### Task 2: Primitive Data Types

1. Create a multi-line string using template literals that describes Fluffy’s daily routine. 
Include at least three activities.
2. Use the `typeof` operator to check the data type of dog, age, and the multi-line string you just created. Print the results to the console.
3. Create a boolean variable `isGoodBoy` and set it to `true`. 
Then create a variable `favoriteFood` and leave it undefined.
4. Perform basic numerical operations: 
    - Calculate how many dog years old Fluffy is (1 human year = 7 dog years) and store the result in a new variable.
    - If Fluffy eats 2 cups of food per day, calculate how much food he eats in a month (assume 30 days) and store the result in a new variable.
5. Create a string `dogInfo` and use string concatenation to build a sentence about Fluffy. Include his `name`, `age`, and `breed`.
6. Determine the length of the `dogInfo` string and print it to the console.
7. Fluffy's owner is trying to calculate the total cost of Fluffy's care. Create variables for: 
    - Monthly food cost
    - Yearly vet checkups (2 per year)
    - Daily treat cost
    
    Calculate the yearly cost using one complex expression that requires correct use of parentheses (*remember PEMDAS).* Add a meaningful comment describing it.
    

### Task 3: String Manipulation

1. Access the first character of Fluffy's name using both bracket notation and the `charAt()` method. Print both results to the console.
2. Find the index of the letter 'f' in Fluffy's name using the `indexOf()` method. 
Print the result to the console.
3. Create a string variable `dogPhrase` with the value "Fluffy loves to swim in Regent’s Park".
    1. Use the `indexOf()` method to find if the word "swim" exists in the string.
    2. If it does, use substring extraction to create a new string `favoriteActivity` that contains only "swim".
4. Fluffy's owner decides to nickname him "Fluffster". Use the `replace()` method to change "Fluffy" to "Fluffster" in the `dogPhrase` string.
5. Fluffy has many nicknames! Replace all instances of "Fluff" with "Puff" in the following string:
"Fluffy, also known as Fluffster and Sir Fluff-a-lot, is a very fluffy dog."
6. Convert Fluffy's name to uppercase and then to lowercase. Print both results to the console.

### Task 4: Operators and Conditionals

1. We learnt Fluffy’s age earlier in this exercise. Use a comparison operator to check if Fluffy’s age is greater than 10 and store the result in a boolean variable called `isFluffySenior` .

Print the following message to the console:
“Is Fluffy a senior dog?” followed by the value of `isFluffySenior` .
2. Create a new variable called `fluffyName` and set it to “FLUFFY”.
3. Use a comparison operator to check if `fluffyName` is exactly equal to “FLUFFY” (remember, this is case sensitive). Store the result in a boolean variable called `isExactMatch` .
4. Create a new variable called `fluffyEnergyLevel` and set it equal to 8. 
Write an `if` statement to check if Fluffy needs a walk. If fluffy’s energy level is greater than 7, print a message to the console to take him for a walk.
5. Create a variable called `weatherCondition` and set it equal to “rainy”.  Determine what activity fluffy should do based on the weather using an `if-else if-else` statement.

If the `weatherCondition` is “sunny”, print “Take fluffy to the park!”.
If the `weatherCondition` is “rainy”, print “Indoor playtime for Fluffy!”.
If it’s neither, print “Straight up cuddles with Fluffy!”.

6. Create a new boolean variable called `isHungry` and set it to `true`.

Enhance the previous`if` statement above so that if `weatherCondition` is “rainy”, check `isHungry` and if the value is `true` , print “Indoor playtime and dinner for Fluffy!”.

If `isHungry` is `false` , print “Indoor playtime for Fluffy!”. 

### Task 5: Control Structures

1. Create a `for` loop that runs 7 times, representing the 7 days of the week. For each iteration, print: “Day [number]: Fluffy wakes up, eats, plays, and sleeps!”
2. Create a variable `treatsGiven` and set it to 0 and a variable `maxTreats` and set it to 3.
Use a `do…while` loop to give Fluffy treats. In each iteration, increment `treatsGiven` by 1 and print “Fluffy says: Woof! Thanks for treat #`treatsGiven` ”. Continue the loop while `treatsGiven` is less than `maxTreats` .
3. Create a variable `dayOfWeek` and set it to "Wednesday".
Use a `switch` statement to determine Fluffy's meal for the day.
For each day, print: "Fluffy's [day] meal: [meal]"

- Monday: Chicken
- Tuesday: Beef
- Wednesday: Fish
- Thursday: Turkey
- Friday: Veggie Mix
- Saturday and Sunday: Special Weekend Blend
- For any other day: Kibble

## Submission

When you’ve completed the exercise:

1. Run the following commands:

```jsx
git add .
git commit -m "Completed Fundamental JavaScript with Fluffy"
git push origin main
```

1. Create a Pull Request and submit your assignment below:

< Submission >

Please provide the link to the Pull Request you’ve created for the Exercise.

## Bonus Challenge

If you’re up for a little extra challenge, you can try this:

### Task 6: Fluffy’s Rainy Day Indoor Games

Fluffy loves playing indoor games on rainy days. Let's simulate a series of coin tosses (heads and tails) to decide which games Fluffy gets to play!

Create a variable `numberOfGames` and set it to 5.

Create a variable `tailsCount` and set it to 0.

Use a `for` loop that runs for the `numberOfGames`.

For each game, generate a random number between 0 and 1.

If the number is less than 0.5, consider it “tails”, increment `tailsCount` by 1 and print: 
"Game [number]: Tails! Fluffy gets a treat!"

If the number is greater than or equal to 0.5, consider it “heads” and print:
”Game [number]: Heads! Fluffy does a trick!"

After the loop has finished running, print: 
"Game day complete! Fluffy got [tailsCount] treats out of [numberOfGames] games."

Happy Coding! 🚀

## Frequently Asked Questions (FAQ)

- **How do I run my JavaScript code?**
    
    Use the Live Server extension in VS Code. Right-click on your HTML file and select "Open with Live Server". Your code will run in the browser, and you can see the output in the browser's console (usually accessible by pressing F12).
    
- **Is JavaScript case-sensitive?**
    
    Yes, JavaScript is case-sensitive. `myVariable` and `myvariable` would be treated as two different variables.
    
- **My** `if` **statement isn't working as expected. What could be wrong?**
    
    Double-check your condition. Make sure you're using comparison operators (==, ===, <, >, etc.) and not assignment operators (=).
    

- **My loop is running infinitely. How do I stop it?**
    
    Make sure your loop condition will eventually become false. For while loops, ensure you're updating the condition variable inside the loop.
    
- **How do I generate a random number between 0 and 1?**
    
    If you want to generate a random number between 0 and 1, you can use:
    `Math.random()` . This generates a floating point number.
    

- **What's the difference between** == **and** ===**?**
    
    == compares values and performs type coercion, while === compares both value and type without coercion. It is generally safer to use === for an exact comparison.
