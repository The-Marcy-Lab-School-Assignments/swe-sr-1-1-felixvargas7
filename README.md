# swe-sr-1-1

Welcome to your first short response assignment! If the code that you write is what gets your foot in the door for a job interview, how you communicate is what will get you the job. So, treat these assignments seriously! Write your responses as if you were planning on publishing them in a blog for the world to see (and, if you're confident, actually publish them!).

## Setup

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/how-tos/working-with-assignments#how-to-work-on-assignments).

Here are some useful commands to remember.

```sh
npm i                   # install dependencies
git checkout -b draft   # switch to the draft branch before starting

git add -A              # add a changed file to the staging area
git commit -m 'message' # create a commit with the changes
git push                # push the new commit to the remote repo
```

## Prompt

Imagine you are teaching a brand new programmer a brief lesson about functions and function calls. Your lesson should have the following components:

* A technical definition ("According to MDN, a function is...").
* An explanation of the concept with an analogy ("You can think of a function a ...")
* An example of the syntax for an arrow function using a JavaScript code block (triple backticks)
* An explanation of the syntax using the terms **arrow function**, **parameter**, **code block**, **return statement**, and **call/invoke**.

Below, we've provided an outline for your response but feel free to modify it as you see fit.

### Response

    In MDN, a function is defined as one of the fundamental building blocks when working in JavaScript. It entails a set of statements that perform a task or action, usually by invoking or calling a function. A function consists of a declaration, a method to start off the function, a function name, parameters wrapped in parenthesis used as placeholders, curly braces to enclose a functions code, the actual code and finally a return statement used an output of the code provided. A function can be better understood with the idea of cooking; you would start off with a recipe, which would be the function itself, the ingredients would be parameters, the code would be the cooking instructions, and the return/execution would be the final dish you've made.

A common syntax used for functions in JavaScript is the arrow function:

```js

const funTime = (person, isFun) => {
    let thisFun = person + isFun;
        return thisFun;
};
console.log(funTime("Felix", "is very fun!")); // Will print out "Felix is very fun!" in terminal

``` 

    In my example, I provided an arrow function "funTime". I first had to declare the function with "const", which allows me to declare of function expression, assigning it in this case to a "const" variable. The "const" declaration ensures the function cannot be reassigned to a different value later in the code. I can also use the "let" declaration to allow me to reassign the value later on. Following the declaration, I name the function funTime, followed by an equal sign, which then move onto the parameters of this fucntion. I put two parameters, which are simply name holders for the values that will be passed into the function when invoking it, each seperated by commas. It's important to note that parameters are optional and not necessarily required, however they are recommended for code readability and clarity, as well as flexibility for your code. After parameters, the "=>" symbol is used to transition into the body of the function, which is also the reason for calling this function an arrow function. 
    
    After the arrow symbol, the curly brackets encapsule the body of the function where the code will perform the functions operation. In my case, I declared a variable inside my function with the let statement because I want it to stay flexible, and I make the variable "thisFun" equal to the parameters "person" plus "isFun". I also put a return statement, "return thisFun;", which is simply a way to specify the function will be outputting code back to the part of the code that called it, essentially executing the code. I then close the function with the second curly bracket used to hold the body of the function, and finally adding the function into "console.log(funTime("Felix", "is very fun!"));". Notice I ended up filling the "funTime" parameters "person" and "isFun", with the now arguments "Felix" and "is very fun!" respectively. Arguments are the actually values we use when calling a function, replacing the previous name holder parameters. The "console.log" ends up allowing me to call on the code and see the result of my code in the terminal console, which for our purpose I place in a comment "// Will print out "Felix is very fun!" in terminal". One small thing to note here is the use of ";" which is the equivalent of using periods "." in english. It allows us to show the code that we are done with one line of code, and would like to move on from one setence to another basically. 


[Replace with your explanation of the example and explanation of the syntax]
