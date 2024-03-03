# Variables

Variables allow you to store information that can be accessed over and over again. These are similar to variables in algebra. But in programming, we name our variables according to the syntax of that language. 

Naming a variable is called *declaring a variable*.

In English for example, we might say:

![Alt text](<img/Command Line and Batch File Basics V28.png>)

Here the equals sign `=` is the *assignment* operator. It lets us know that we have assigned the string `Amanda` to the variable, `name`.

> After reading this, you will want to check out [Types - what are things?](/types.md). It will explain what we mean by `string`. 

![Alt text](<img/Command Line and Batch File Basics V29.png>)

### Variables are like buckets

![Alt text](<img/Command Line and Batch File Basics V210.png>)

The bucket now contains sand.

I don’t need to know what is in the bucket, I can just ask “what’s in the bucket named `my_bucket`?”

When I ask what is in the bucket, I will be told that it is sand.

If I add water to the bucket, *it first empties the bucket automagically*.

![Alt text](<img/Command Line and Batch File Basics V211.png>)

Variables are *mutable*. Which is a posh way of saying "they can be changed".

Now when I ask “what’s in the bucket named `my_bucket`?”

I will be told it contains water.

## Pseudocode

I will use pseudocode - code that looks real, but doesn't always mean it's executable or any particular language.

```
var my_bucket = "sand"
print my_bucket //print out "sand"
```

## What things can a bucket hold?

Well, buckets can hold whatever you tell them they are. Your magic bucket will hold whatever you put in it.

However, many programming languages will only let your variable hold the same type of thing as it first held.

So in our examples above, water is a *type* of liquid. So we would replace the water with milk, or coca cola, or even liquid nitrogen - as those are all *types* of liquid.

Many programming languages won't let us replace water with sand, as sand is not the same type - it's clearly not a liquid!

If you're looking at programming further, then you'll need to know more about the [types](/types.md) that variables can be...
