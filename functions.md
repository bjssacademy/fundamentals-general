# Functions

Part of programming involves making things reusable, and cutting down on repeated code that is exactly the same.

The main reason for this is two-fold:

1. Code that is repeatedly copied and pasted is prone to errors.
2. If it changes in one place to fix a bug, then it needs to change in *all* places where it has been copied to.

## So what's a function?

Without trying to get all "maths-y", a function a thing that does something the same way every time you "call" it. 

> I'll use the word "call", but you'll see the term "invoke" used elsewhere.

Functions are one kind of programming building block. It's a block of code that performs a specific task. Just like how you might have different tools in a toolbox for different jobs, a function is a tool that helps a computer perform specific tasks or calculations.

Think of a function like a recipe in a cookbook. You have a list of ingredients (inputs) and a set of instructions (code) to follow. When you "call" or "use" the function, you provide it with the necessary ingredients (arguments), and it executes the instructions, producing a result (output).

You can use them without knowing how they work inside.

## Okay, can you give me a non-code example?

Yes, of course!

Taking our earlier example of a cookbook, let's say we don't know how to cook, but we do know a friendly chef who will work for free as long as we provide the ingredients.

We can call our chef friend up and give him the ingredients, and he'll return a us a cooked dinner!

That's pretty much how functions work. Here the *chef* is a function.

He accepts ingredients, and *returns* a cooked dinner.

When we say a function accepts thing - like ingredients - these are known as *parameters*.

In short:

```
function chef accepts ingredients and returns meal
```

1. function name: chef
2. function parameters: ingredients
3. function returns: meal

## Okay, what does that look like in code?

Well, that depends on the language. But in Go it might look something like:

```go
func chef(ingredients []Ingredient) Meal {
    // Create a new meal
    meal := Meal{
        Name:       "Delicious meal",
        Ingredients: ingredients,
    }
    return meal
}
```

You can see that every time we call this function, it will return to us a delicious meal!

## But why is this useful?

Well, imagine now we had to call a different chef for every single different combination of ingredients depending on what we had in our fridge!

We'd quickly run out of space, and our code would be very confusing. 

Using functions also allows us to *abs*tract the problem, and provide a simple interface to cooking dinner.

## Abstraction?

Abstraction involves simplifying systems by hiding unnecessary details - for instance, you don't care about cooking, but you know a chef. 

Functions abstract away the implementation details by providing an interface that allows us to interact with them without needing to know the underlying complexities - like how or what to cook given a list of ingredients. 

We can call functions to perform tasks without having to understand how those tasks are achieved internally!