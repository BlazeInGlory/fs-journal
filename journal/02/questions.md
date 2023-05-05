# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

  let, var, if(?)

02. What is the definition of a function?

basically making arguments that perform tasks for you, an input for an output.

03. What are the `SOLID` principles?

single responsibility principle,
open closed principle,
liskov substitution principle,
interface segregation principle,
dependency inversion principle

(i'm gonna be honest, i had to look these up, but I read up on each of them and became somewhat familiar with them)

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

list [0, 1, 3, 4]

05. Given these two objects: How could you add each to the others friends arrays?

    ```js
    let you = {
        name: "You",
        hair: true,
        friends: []
    }
    let them = {
        name: "Them",
        hair: false,
        friends: []
    }
    ```

  push()

06. Give an example of a JavaScript `Conditional`:

if x <= 13
console.log(x)

07. What is the main difference between `parameters` and `arguments`?

 objects vs. values I'm pretty sure.

08. Instead of writing everything to the console, what is a better way to debug your code?

Literally type debugging in your script, and then play/pause each step until you find the issue.

09. What is the difference between a `primitive` value and a `reference` value?

primitive is more specific, reference is like the whole value of something.

10. Demonstrate a loop that prints the numbers between -100 and 100?

x = 100
for (x <= 100);
x--
for (x >= -100);
x++
