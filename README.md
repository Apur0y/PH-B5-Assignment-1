

Have a look on the  union and intersection types in TypeScript:
Let’s break down two things I think every TypeScript dev should know—union vs intersection types, and the difference between any, unknown, and never. First, union types (A | B) let a variable hold either one type or another, like when a function takes a string or number. For example, function printId(id: string | number) means id can be a string or a number—nice and flexible. On the other hand, intersection types (A & B) are used when you need to combine multiple types into one. Say you have a User type and an Admin type, using User & Admin means your object must have all the properties from both.

Let's talk about the difference between any, unknown, and never types in TypeScript:
Any, unknown, and never—these confuse a lot of people, but they’re actually simple when you get them. any disables type checking (kind of dangerous), unknown is safer because it forces you to check the type before using it, and never is for values that should never happen (like a function that always throws an error). Learning these will not only help you write better TypeScript, but also avoid silly bugs and make your code easier to manage later.
