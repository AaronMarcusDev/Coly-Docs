# Macros

In Coly we use macros to reduce the amount of code we have to write.
A macro is a collection of code that can be called with a single keyword.

## Defining a macro

To define a macro, we use the `macro` keyword.\
The syntax is as follows:

```css
macro <name> {
    <code>
}
```

## Using a macro

To use a macro, simply use the macro name as a keyword.\
Example:

```css
macro hello { // defining the hello macro
    "Hello, world!" puts
}

hello // calling the hello macro
```

Output:
```
$ Hello, world!
```

Previous: [Operators](operators.md)