# Syntax

For an example of a syntactically valid file, see the [prelude](prelude)

## Statements

A source file consists of a number of statements, separated by newlines

A statement is either of the form `let varname = ...` or `assume x :: ...`.

## Functions

All functions are defined using lambda syntax: `\`, the space-separated arguments, `->`, then the function body.

```haskell
(\ x y -> x)
```
