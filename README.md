# Front-end Job Interview Questions: My Answers!

This file contains my personal(some research included in 'personal') answers to a number of front-end interview questions from [https://github.com/h5bp/Front-end-Developer-Interview-Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions)

## Table of Contents

  1. [General Questions](#general-questions)
  1. [HTML Questions](#html-questions)
  1. [CSS Questions](#css-questions)
  1. [JS Questions](#js-questions)
  1. [Testing Questions](#testing-questions)
  1. [Performance Questions](#performance-questions)
  1. [Network Questions](#network-questions)
  1. [Coding Questions](#coding-questions)

#### General Questions:

* What did you learn yesterday/this week?

   *Object.create is a constructor pattern created by Douglas Crockford to offer a less "obscured" method than the 'new Object'.*
   
* What excites or interests you about coding?

   *The infinite possibilities, the power of creation.*

#### HTML Questions:

* What does a `doctype` do?

   *Doctype is a required declaration to inform the brower the HTML version used in the page, also required for legacy reasons.*

#### CSS Questions:

* What is the difference between classes and IDs in CSS?

   *1 - Class uses a period(.) followed by the name of the class, can be used on a group of elements with common attributes.*
   
   *2 - ID uses the hash(#) followed by the name of the ID, should be unique and it's more specificic than classes(overrides the same attributes setted by classes of that element).*

#### JS Questions:

* Explain event delegation

   *A pattern used to assign an event handler to the parent or a common ancestor of the elements. Is commonly used to avoid batch assignments.*

#### Testing Questions:

* What are some advantages/disadvantages to testing your code?

   * Advantages: reduces code refactoring time, reduces long-term costs, delivery a safer code.*
   * Advantages: increases workflow complexibility, increases short-term costs.*

#### Performance Questions:

* What tools would you use to find a performance bug in your code?

   *Chrome Devtools Timeline with the paint flashing option on.*

#### Network Questions:

* Traditionally, why has it been better to serve site assets from multiple domains?

   *HTTP1.1 can't handle multiplexing, only one request can be outstanding on a connection at a time using the current protocol. One workaround is to use multiple source domains.*

#### Coding Questions:

* Question: What is the value of `foo`? *
```javascript
var foo = 10 + '20';
```
   *Due to JS internal type coercion rules, the result is the string "1020"*
