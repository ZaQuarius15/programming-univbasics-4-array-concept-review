# Array Concepts

## Learning Goals

- Recognize array as a core programming tool
- Recognize array vocabulary word: Element
- Recognize array vocabulary word: Index
- Recognize array core property: Ordering
- View an `Array` in Ruby

## Introduction

Much of life is understood by grouping things together based on a common
characteristic. For instance, here are some groups you might have heard of:

- Family last name (The Simpsons)
- Band name (e.g. The Beatles)
- Grocery list

In most programming languages, the thing for storing a collection is called an
"array". Arrays, as we'll learn, can also be used to order the things in the
collection ("get the youngest Simpson" or "last grocery item").

Working with arrays is one of the most important tools to master in your
programming career. In this lesson we'll make sure we know the vocabulary for
working with arrays.

## Recognize Array As a Core Programming Tool

The bulk of **_all_** programming work is taking inputs, doing some change to
them (combining them, filtering them, attaching them together, etc.), and
producing new output. 

An array allows programmers

1. To create variables that store the input or output
2. To create variables that tell other programmers "there are a bunch of
   individuals data bits here, but, together, they make up something else, a
   _collection_, and knowing that fact is important."

Like all _data structures_, the `Array` has rules and we'll explore them in
this lesson.

### Example Data

<iframe width="560" height="315" src="https://www.youtube.com/embed/FX20kcp7j5c" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

Let's establish an example for the rest of this lesson: the Shark Family as
ordered by age, youngest to oldest. To keep things simple, we'll express this
list in English, not in any programming language. In English, we tend to start
numbering (or _indexing_) at `1`, not `0`, but the reverse is true in the
programming world.

1.  "Baby Shark"
2.  "Mama Shark"
3.  "Papa Shark"
4.  "Grandma Shark"
5.  "Grandpa Shark"

## Recognize Array Vocabulary Word: Element

An individual member of an array is called an _element_. In our example, "Baby
Shark" is an _element_. "Grandma Shark" is also an element. All arrays are
collections of _elements_.

## Recognize Array Vocabulary Word: Index

Earlier we mentioned that _data structures_ have rules. **The main rule of the
array data structure is that the individual _elements_ in an array can be
"pointed to" by providing a number (Integer) and the name of the array.**

In our example, we might say that in the lowest index (`1`) of the "Shark
Family" array, we have "Baby Shark." In the highest index (`6`) of the "Shark
Family" array, we have "Grandpa Shark."

## Recognize Array Core Property: Ordering

Because arrays' _elements_ are _indexed_ by numbers that increase from a
starting number by whole numbers, arrays can be used to keep _elements_ in
order.

Arrays can hold elements that aren't sorted (like "The Beatles" above), but
programmers use the ordering property of the indexes to keep the collection in
order. If the Shark family had a *new* baby shark we would put her in index 1
and move all the other sharks up one.

1. "Newborn Baby Sister Shark"
2. "Baby Shark"
3. "Mama Shark"
4. "Papa Shark"
5. "Grandma Shark"
6. "Grandpa Shark"

You'll have the chance to work with the ordering property hands-on shortly.

Let's look at our Shark family in the language of code.

## View an `Array` in Ruby

In this example, imagine that the constant `SHARK_FAMILY` points to an `Array`
and has already been defined for us (we'll learn to define `Array`s in a
moment).

In Ruby, we can print out an Array's contents with `p` and the name of the
`Array`. Here, in IRB, we are printing out `SHARK_FAMILY`:

```ruby
2.3.3 :003 > p SHARK_FAMILY
["Baby Shark", "Mama Shark", "Papa Shark", "Grandma Shark", "Grandpa Shark"]
 => ["Baby Shark", "Mama Shark", "Papa Shark", "Grandma Shark", "Grandpa Shark"]
```

Ruby prints out the `Array` by putting square-brackets (`[]`) at the beginning
and end of the `Array`. Between the brackets, it lists each of the elements,
separated by commas (`,`). It _does not_ show the indexes of each of the
elements.

Looking at this output, we can see that there are 5 shark family members. At
the lowest index, or "index 0" of `SHARK_FAMILY`, is "Baby Shark." At the
largest index, or "index 4" of `SHARK_FAMILY`, is "Grandpa Shark."

## Conclusion

In this lesson, we learned about the data structure `Array`. From iPhone to
Java to Python, nearly every programming language has something like an
`Array`. Arrays are composed of _elements_ which are accessed by an _index_.
Indexes move upward from `0` in Ruby and JavaScript. Arrays are often displayed
in programming documentation in _array literal syntax_ which is brackets (`[]`)
filled with _elements_ separated by `,`s. 

## Resources

- [Arrays][]
- [Literals][]

[array doc]: http://ruby-doc.org/core-2.3.4/Array.html#method-c-new
[Arrays]: http://ruby-doc.org/core-2.3.4/Array.html
[literals]: https://docs.ruby-lang.org/en/2.0.0/syntax/literals_rdoc.html
[literal]: https://docs.ruby-lang.org/en/2.0.0/syntax/literals_rdoc.html
[batman]: https://www.youtube.com/watch?v=VSaDPc1Cs5U
