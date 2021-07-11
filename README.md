# Introduction to Self

For newly developing Rubyists, `self` can be a bit baffling. You've learned
about the concept of the class, and that each object in Ruby has one. The
keyword `self` is a special variable that points to the object that "owns" the
currently executing code. You can think of it as a Ruby program asking, "who am
I right now?". Ruby is using the concept of `self` to determine which execution
context to use at any point in the program.

`self` in Ruby is used in a similar way to `this` in Object-Oriented JavaScript,
with a few key differences that we'll cover over the course of this section.

In these few lessons, we'll demonstrate:

- How the `self` keyword works
- How to use `self` within an instance method to refer to the class instance on
  which that method is being called
- The concept of monkey patching Ruby's built-in classes
- How to use `attr_accessor`, `attr_reader`, and `attr_writer` as needed

In this section, we're going to talk about how to use `self`, and how to apply
`self` in a variety of situations.
