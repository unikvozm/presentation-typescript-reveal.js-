# Presentation-Q3-2019

## Typescript

[Click here to see the slides](https://jovial-ardinghelli-9b72f2.netlify.com/)

`(Slide 1 TypeScript)`
Hi everyone. My name is **Nataly**. I’ve made a career in Finance and Tutoring and now my goal is an IT field.
So, Today I’m going to talk about TypeScript. Why TypeScript? Just because it’s gaining popularity among developers and appears in job postings quite frequently.

`(Slide 2 Structure)`
In this presentation we’ll consider what TypeScript really is, what kind of opportunities it creates, what problems you can face working with it, then I’ll show you some statistics to prove its popularity and at the end we’ll take a look for its alternatives.
So, let’s begin!

`(Slide 3 What is it?)`
Well, **TypeScript** is an open source programming language created by Microsoft.
The most important difference between TypeScript and JavaScript is that they’re two separate programming languages, though TypeScript is heavily based on JavaScript. It’s a _superset of JavaScript_ meaning that all valid JavaScript code is also valid TypeScript code.
Typescript doesn’t alter JavaScript, instead expanding it with lots of other features. Its most important feature is the possibility of _static typing_. That means that you can define a type of your variables (for example, number, string or Boolean types).
TypeScript has also support for _interfaces, enums and other things_ that you don’t find in JavaScript.
In fact, TypeScript is based on **.NET harmony specification**, so lot of code looks and behaves similarly to .NET and other object-oriented programming languages.

`(Slide 4a Advantages)`
Let’s consider its advantages.

- **Type checking** is definitely the biggest advantage of TypeScript. Its usage eliminates many randomly generated bugs that result from unreliable data types.
  Let’s say one developer created a sumOfTwo function and used types to define that the function can only take 2 numbers. If another developer tries to provide a string to the function, TypeScript will return an error, whereas in JavaScript such an operation would be perfectly acceptable.
- So, In JavaScript, you’ll only find errors once you use the app. But in TypeScript, when a developer makes a mistake and enters unsupported input into the code, they’ll be made aware of it before pushing the code to the repository.

`(Slide 4b Advantages)`
Typescript is **a time-saver** due to some its features.

- Thanks to compile-time type-checking, the programmer can focus on the development of an application and don’t waste time unnecessarily on searching and analyzing the resulting errors.
- In addition to displaying the errors at compile time, certain IDEs such as Visual Studio Code will present the errors to the developer while they are typing the code. This makes correcting simple careless errors much quicker and easier.
- Because of type-checking, we don’t need to test whether our function arguments are being passed between each other correctly. Less tests means shorter time to develop new features, and a smaller codebase.

`(Slide 4c Advantages)`
The next benefit of TypeScript is that it can **increase a team performance**.

- First-of-all, explicitly defined data structures and type annotations make it incomparably _easier to understand_ the decisions made by the engineers originally writing the code.
- In fact, providing types is a kind of documenting code. This is often referred to as _“self-documenting code”_ meaning that one developer writes something, and others know what it does and how just by looking at it.
- Additionally, there’s often quite a lot of things you’d like to refactor, but because they touch so many things and files, you’re just too afraid of changing them. In TypeScript, such things can often be refactored with just one click of **“Rename Symbol”** command in your IDE.

`(Slide 4d Advantages)`
Another great advantage of TypeScript is that it mixes the old with the new in the best way possibility. You can use newer features from ES6, ES7, and beyond, and the compiler will convert them to ES5 (or whatever you specify). This allows your team to make _use of newer features_ that will be the future of JavaScript without having to worry about compatibility.

`(Slide 5 Disadvantages)`
However, there are some **drawbacks of TypeScript**.
One of the arguments against TypeScript is that it **requires compilation**, while JavaScript doesn't. But, let’s be honest, most of JavaScript applications these days require a build step. Whether it’s Gulp, Grunt, Webpack, Babel, or Closure — a build step is a necessity and nothing really prevents you from expanding it.
Another problem is some **additional difficulties in a set-up stage**. For example, what is the difference between a Next.js app and a Next.js app in TypeScript? In the second case, you need to make your Node.js server, webpack, and jest test runner to work with TypeScript. Also, whenever you add some library like React, Redux, Styled-Components, you also need to add typedefs for it.

`(Slide 6a Statistics)`
Overall, statistics shows that many developers are taking advantage of TypeScript’s features.

`(Slide 6b Statistics)` According to the most recent StackOverflow Developer Survey, TypeScript cracked the Top 10 of the most popular Technologies.

`(Slide 6c Statistics)`... and it is the third loved technology among developers.

`(Slide 7 Alternatives)`
However, TypeScript isn’t the only tool that brings types to JavaScript or frontend development in general. There are also others, and we’ll now take a look at those.

- **Flow** is also a superset of JavaScript, but it isn’t categorized as a separate language. Like TypeScript, Flow offers type annotations… and that’s pretty much it. No additional syntax, everything is the same as in JavaScript. But in 2019, Facebook decided to move Jest—one of its most popular projects—from Flow to TypeScript. I believe this speaks for itself.
- **JSDoc** is a living standard for documenting JavaScript code. It allows you to not only use text to write what each piece of code is doing, but also annotate types. But proper typing with JSDoc is difficult and it requires a lot more code than TypeScript.
- There’s also a number of languages that provide a strict type system and can be compiled to frontend code one way or another (like **Kotlin, Rust, Go, Elm and Reason**), but TypeScript has one key advantage over them that makes it more suitable for frontend development: _TypeScript is far easier to learn for current JavaScript developers, mainly because it’s just augmented JavaScript_.

`(Slide 8 Thank you)`
So, all things considered, TypeScript is a fantastic tool for JavaScript developers. It makes working on larger projects easier and provides a better code-writing toolkit that can greatly improve your software development process.
Thank you and Good coding!

