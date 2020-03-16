# Callback Hell

## Story

We have a huge problem, the Callback Hell of JavaScript has opened up and it is threatening the developer world with total destruction! We can already see the Pyramid of Doom down there, so this is no joke. You have to pick up some explosives and blow the whole thing out of existence to save our precious world (and StackOverflow)!

The task is easy, you need to deploy a bomb and notify others when it is going to blow up.
    You can communicate through a website with a terminal-like view
    and update it with the counting down in real time: "3... 2... 1... Boom!"

## What are you going to learn?

Execution flow in JavaScript is different from most languages so we'll check out some of its essential features to understand it better:

- how to structure JavaScript code and make sense of callbacks when using `setTimeout` and event handlers
- the event driven nature of JavaScript
- that functions can be passed inside other functions as arguments
- JavaScript Promise basics

## Tasks


1. Implement real time countdown by using `setTimeout()` and callbacks

    - The countdown sequence shows up in real time:
  - print "The bomb goes off in..."
  - wait 1s
  - print "3..."
  - wait 1s
  - print "2..."
  - wait 1s
  - print "1..."
  - wait 1s
  - print "Boom!"

2. [OPTIONAL] Implement the same task, but this time use JavaScript Promises

    - The countdown sequence shows up in real time, and the execution flow is controlled by Promises.


## General requirements


 - Only `printText()` and `clear()` from `common.js` are used for DOM manipulation.

## Hints

- You can open `index.html` by starting a small Python server (without Flask this time) with this command in the project folder: `python3 -m http.server -b 127.0.0.1` (or you can just open it directly in a browser, but we would recommend the first method).

## Starting repository

Click here to clone your own Git repository:
<https://journey.code.cool/v2/project/solo/callback-hell>

## Background materials

- :exclamation: [What is a callback?](https://learn.code.cool/full-stack/#/../pages/javascript/what-is-callback)
- :exclamation: [Demolish the Callback Hell: a step-by-step project guide](https://learn.code.cool/full-stack/#/../pages/javascript/demolish-callback-hell.md)
- :lollipop: [Demolish the Callback Hell code examples hosted online](https://repl.it/@szrudi/JS-Callback-hell-tutorial)
- :exclamation: [Another callback hell example and how to fix it](http://callbackhell.com/)
- :open_book: [JavaScript: What the heck is a Callback?](https://codeburst.io/javascript-what-the-heck-is-a-callback-aba4da2deced)
- :open_book: [More in depth reading on callbacks with some mind-bending examples](https://javascript.info/callbacks)
- :open_book: [Serving a Burger - How to avoid callback hell](https://www.freecodecamp.org/news/how-to-deal-with-nested-callbacks-and-avoid-callback-hell-1bc8dc4a2012/)
- :lollipop: [Promise basics](https://javascript.info/promise-basics)
- :lollipop: [MDN - Promises](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Promises)
- :lollipop: [MDN - Using promises](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Using_promises)
- :lollipop: [Promise tutorial code](https://repl.it/@szrudi/Promise-to-wake-Neo)

## Acceptance review

You will need this only at review time, **after** completing the project.
[Use this form](https://forms.gle/7GDaRXZNm6MNkNPw9) to record the review you provide for your peer.