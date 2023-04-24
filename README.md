# Boolean-Logic-Exercises

## **Part I**
<!-- Write down what the following statements will return. Try to figure this out before putting the commands in the chrome console. -->
1- 2 == “2”; true
2- 2 === 2; true 
3- 10 % 3; 1
4- 10 % 3 === 1; true
5- true && false; false
6- false || true; true
7- true || false; true


## **Part II**
<!-- Answer the following questions about this code block: -->
    let isLearning = true;
if(isLearning){
  console.log("Keep it up!");
} else {
  console.log("Pretty sure you are learning....");
}

1- What should the above code console.log?
    Keep it up!

2- Why do we not need to specify if(isLearning === true)? Why does if(isLearning) work on its own?


<!-- ************************************************ -->
let firstVariable;
let secondVariable = "";
let thirdVariable = 1;
let secretMessage = "Shh!";

if(firstVariable){
  console.log("first");
} else if(firstVariable || secondVariable){
  console.log("second");
} else if(firstVariable || thirdVariable){
  console.log("third");
} else {
  console.log("fourth");
}

1. What should the above code console.log? Why?
    will console log "third" because firstVariable is undefinded so its false and the second condition empty string is undefined too so false or fasle give us false.

2. What is the value of firstVariable when it is initialized? 
    undefined

3. Is the value of firstVariable a “truthy” value? Why?
    no because it undefined value

4. Is the value of secondVariable a “truthy” value? Why?
    no because it's empty string

5. Is the value of thirdVariable a “truthy” value? Why?
    yes because it's a number.




## **Part III**

1. Research  [here]([https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random))
    
    ***Math.random***
    
Write an if statement that console.log’s “Over 0.5” if ***Math.random*** returns a number greater than 0.5.
    Otherwise console.log “Under 0.5”.

    let number = Math.random();

    if (number > 0.5) console.log(`${number} is Over 0.5`);
    else if (number < 0.5) console.log(`${number} is Under 0.5`);
    else console.log(`${number} is  0.5`);

2. What is a falsey value? List all the falsey values in JavaScript.
    Null 
    ""
    NaN
    undefined
    0