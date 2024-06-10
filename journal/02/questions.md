# Intro to JavaScript
01. Which keywords are used to declare a variable in JavaScript?

    > The keywords are let, var, and const.

02. What is the definition of a function?

    > A function is a clump of code that will play out when it is called at another place. It is basically like making a mini snippet that can be called wherever instead of writing all of the code over and over.

03. What are the `SOLID` principles?

    > The single-responsibility principle
    > The open-closed principle
    > The Liskov substitution priniciple
    > The interface segregation principle
    > The dependency inversion principle

04. Given this array: How could you remove the `pineapple`?

    ```js
    let fruit = ['apple', 'banana', 'pineapple', 'orange', 'strawberry']
    ```

    > fruit.splice(2,1)

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

    > friends.push(you) 
    > friends.push(them)

06. Give an example of a JavaScript `Conditional`:

    > A conditional is a chunk of code that is only run when a different part becomes true. When the other part is not true, the conditional does nothing.

07. What is the main difference between `parameters` and `arguments`?

    > A parameter is the variable in the declaration of the the function. It is inside of the parentheses.
    An argument is the physical value of the variable that gets passed to the function.

08. Instead of writing everything to the console, what is a better way to debug your code?

    > | ANSWER HERE |

09. What is the difference between a `primitive` value and a `reference` value?

    > | ANSWER HERE |

10. Demonstrate a loop that prints the numbers between -100 and 100?

    > for(let i = -100, i <= 100, i++){
        console.log(i)
    }
