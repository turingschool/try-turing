---
layout: lesson
---

<a href="../">Back to Setup Page</a>

# JavaScript Fundamentals

Before we start writing JavaScript code to make this Number Guesser game work, we're going to touch on some fundamentals that will prepare us for that work.

During this section, the code we write and learn about will not yet be connected to our game. It's just for learnings sake!

## Comments in Code

Throughout this resource and accompanying CodePens we will use today, you will see what we call `comments` in code. It is text in a code file that is usually "greyed out" - it's readable by humans but not by the computer or browser. In JavaScript, each comment must have a `//` at the beginning of it:

```js
//this is considered a comment
this is not!
```

## Variables

We can use variables to store and reference information within a JavaScript program. We can think about it as a storage bin in the garage - the contents inside of the bin are what we care about storing, and the label on the outside is how we can quickly identify it.

The syntax for declaring variables and assigning a value to them is as follows:

```js
var age = 23;
// alert(age);

var sum = 3 + 4;
// alert(sum);
```

## Variables and Calculations

Using the two new pieces of knowledge we've acquired, we can combine them to do work like this:

```js
var washCycleMinutes = 38;
var dryCycleMinutes = 45;

var totalLaundryTime = washCycleMinutes + dryCycleMinutes;

alert(totalLaundryTime); // alert message will be: 83
```

<div class="try-it-new">
  <h2>Try It</h2>
  <p>In a new CodePen, declare two variables (name of your choice) and store a value in each one!</p>
  <p>Then use the alert method to ensure it's being stored correctly!</p>
</div>

### Comparisons

JavaScript can also do comparisons! Today, we will focus on comparing numbers.

<div class="try-it-new">
  <h2>Explore to Learn</h2>
  <p>One at a time, copy and paste or type in each line of code below into a CodePen - make sure this is in the JS pane. Predict what the output will be, then observe the alert message.</p>
  <ul>
    <li><code class="try-it-code">alert(3 < 5)</code></li>
    <li><code class="try-it-code">alert(3 > 5)</code></li>
    <li><code class="try-it-code">alert(3 >= 3)</code></li>
    <li><code class="try-it-code">alert(3 === 5)</code></li>
    <li><code class="try-it-code">alert(5 === 5)</code></li>
    <li><code class="try-it-code">alert(5 !== 5)</code></li>
  </ul>
</div>

Exploration Debrief:
- JavaScript can compare two numbers to determine if one is less than, greater than, equal to, or _not_ equal to the other
- JavaScript evaluates a comparison and provides us with a `boolean` - either true or false - as a response

### Conditionals:

An **if statement** sets up different paths that the program can take depending on what is true at a given moment.

<div class="try-it-new">
  <h2>Explore: Reading if Statements</h2>
  <ol>
    <li>Look at the code in the CodePen below. Jot down your prediction of what will happen when we run this code (once line 5 is uncommented).</li>
    <iframe height="265" style="width: 100%;" scrolling="no" title="If Statement Explore/Try It" src="https://codepen.io/turing-trycoding/embed/ZEBezeX?height=265&theme-id=light&default-tab=js,result" frameborder="no" loading="lazy" allowtransparency="true" allowfullscreen="true">
  See the Pen <a href='https://codepen.io/turing-trycoding/pen/ZEBezeX'>If Statement Explore/Try It</a> by Try Coding
  (<a href='https://codepen.io/turing-trycoding'>@turing-trycoding</a>) on <a href='https://codepen.io'>CodePen</a>.</iframe>
    <li>Once you've made your prediction, uncomment line 5 and read the alert. Change the value of the <code class="try-it-code">age</code> variable to test out other situations!</li>
  </ol>
</div>

<div class="try-it-new">
  <h2>Try It: Writing if Statements</h2>
  <p>Follow the prompt in at the bottom of the JS pane <a target="blank" href="https://codepen.io/turing-trycoding/pen/ZEBezeX">in this CodePen.</a> (Same CodePen that was used in previous activity)</p>
</div>

## JavaScript Fundamentals Summary

- JavaScript can store numbers in variables, then do math operations with those variables
- JavaScript can follow certain directions based on conditions we provide

<a href="../js-2">Next Section: Connecting HTML & JavaScript</a>