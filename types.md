# Types - What are things?

Look around you now. Everything is a "thing". Even if you don't know exactly what it is, you can classify it by type.

For instance right now I can see a sofa, a chair, a TV, a bookcase, a charger and so on.

I didn't say they exact make or size of TV, because it's simpler just to talk about the TV.

In programming there are also lots of types - or data types to be exact - and it's important to know the basics of what we are talking about.

## Primitive Types

- Numbers
    - Just like you count numbers, the computer can understand them too. It can be whole numbers called *integers* (like 5, 10) or decimal numbers (like 3.14), which can be called various things in different languages such as *float*, *double*, *decimal*.

- Text
    - Like the words you are reading right now. In programming, we call this type of data a *string* It can be anything from your name to a whole sentence, to an entire book.

- Boolean
    - This is a special type that can only be one of two things: true or false. Like a switch that can be either on or off.

### Most Common Primitives

- string
- boolean
- integer
- float
- double
- decimal

In all programming languages, when you assign a value to a variable, that variable has a *type* associated with it, depending on what it is storing for you.

As an example:

```
var a = "Hello!"
var b = 1
```

The variable `a`'s type is a `string`.

The variable `b`'s type is an `integer`.

## Non-Primitive Types

There are more complex types, but the main one we will talk about here is the `array`.

Arrays are collections of the same things. For instance I said I can see a bookcase from where I am now.

The bookcase is actually a "holder" for many books.

The bookcase itself can have zero or more books on it. Zero when you first build it, then you can add as many as you want until it's full.

In this sense, a bookcase is the word we use as shorthand to say that it is an *array of books*.

You could do this in code by doing something like:

```
var bookcase = array[book1, book2, book3, book4, ...]
```

Here our variable named `bookcase` is a reference to all the books it has on it (`book1`, `book2`, etc).

### Finding Books - Accessing the Array

A very, very, VERY important thing to know about arrays is how you refer to how you find things in them.

To get a single book from the bookcase, you need to know its position, known as the *index*.

Now, we added the books to our bookcase in order, so we'd expect to find `book1` at position 1, or index 1.

Sadly, the world of computers is not like that. The first index available is *zero*.

> I know, I know. You're probably making the same face I did when I came across this many year ago. It's not really important to know why, but it is important to know that arrays are *zero-based*, and that counting starts at 0.

So we can access a single book by using its index. The code for that might look a bit like:

```
var b = bookcase[0]
print b //prints out "book1"

var c = bookcase[1]
print c //prints out "book2"
```
> The square brackets `[]` are how we tell the bookcase array the index we want.

## Other Types

- Objects
    - Objects have properties and behaviours that can be interacted with.
- Classes
    - Classes are blueprints for creating objects. They define the properties (*attributes*) and behaviours (*methods*) that objects of that class will have.
- Lists, Sets, Maps (or Dictionaries)
    - These are more specialized data structures for storing collections of data. Lists maintain an *ordered* sequence of elements, sets store unique elements without any particular order, and maps store *key-value pairs* where each key is unique.