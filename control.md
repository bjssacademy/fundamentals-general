# Control Flow

How do we make decisions? Generally we decide to do one thing over another depending on the result of whichever decision we are faced with.

For example, we might be faced with a decision of whether to turn left or right at a junction.

Based on the result of this decision, we choose one of the two options.

We call the decision a *condition*, and the result of the condition is generally a true or false statement. Thus, we consider a condition as something that evaluates to a simple choice of `true` or `false`.

Expressed in English, this can be as simple as saying:

"If my destination is quicker to get to by turning left, then I will turn left, otherwise I will turn right."

So here what we are evaluating is if the quickest route is served by turning left. Since the decision *only* has a true/false outcome, then the result of that informs which direction we will take.

This is how we control, in the simplest terms, execution of code. We reduce complexity to simpler statements and make decisions.

It's much like having a [flowchart(https://en.wikipedia.org/wiki/Flowchart)], and depending on the condition evaluated, taking the corresponding action.

## Code

If almost all coding languages, the keyword `if` is used to check if a condition is true.

Here's some example code of a made up language. This is a simple piece of code that either does something, or does nothing:

```
if (person reading this is left-handed) {
    say "I am awesome!"
}
```

So, if you are reading this and are left-handed, hopefully you said "I am awesome!" out loud.

If you are right handed, you shouldn't have said anything.

Why?

Well, those curly braces `{}` enclose the outcome of the condition. That is, the code inside those braces is *only* run if the condition is true.

Now, let's try something for the majority of people. We'll add another part of the flow using `else`:

```
if (person reading this is left-handed) {
    say "I am awesome!"
}
else
{
    say "I can buy scissors anywhere!"
}
```

Now, you should only end up saying one of those two statements depending if you are left or right handed.

## Evaluation

When we talk about whether the condition is true or false, we often say we are "evaluating an expression". Again, sounds a bit maths-y and it is a bit, but we'll try to be gentle.

Generally for control flow, we want to evaluate a value stored in a [variable](/variables.md/#variables) that we have been given somehow.

Let's assume there is a variable named `input` that holds a person's name they have typed in.

If that name is "bob", and ONLY if it is "bob", will we print out a special message.

To do that, we want to check for equality. Generally that means using the `==` sign (because in most languages a single `=` is for variable assignment).

So our code might be something like:

```
if (input == "bob") {
    print "Hey Bob, welcome back you superstar!"
}
```

We can check of other things too, but especially numbers:

- < Less Than
- \> Greater Than
- != Not Equal To

There are many others to learn.

## Summary 

For the basics of how we control flow in code, we:

- Evaluate a condition to see if it is true
- If it is true we execute to code block
- Else if it is false, we execute the alternate code block



