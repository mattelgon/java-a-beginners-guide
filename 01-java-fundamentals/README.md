# 1. Java Fundamentals

Term | Notes
----:|:-----
compilation unit | source file, 1+ class defs
access modifier | privilege level, e.g. `public`

## Notes

- compilation units
    - class case should match file case
        - one reason: so compilation artifacts (`x.class`) have the same name
    - `javac` compiles src file to `.class` bytecode
    - `java` interprets bytecode, takes name (without ext) as arg
    - in JDK 11+, can use `java Example.java` to JIT compile and run without outputting `.class` file
        - single-file program only
        - uses first class it finds
- datatypes
    - `int` (supports truncated division)
    - `float` (32 bit)
    - `double` (64 bit, more common)
    - `boolean`
    - `char`
- control flow
    - `if (condition) statement` / `if (condition) statement1 else statement2`
    - `for (init; cond; iter) statement`
    - `break`, `continue`
    - `switch`, `case`, `default`
    - `goto` (!?)
    - `try`, `catch`, `finally`, `throw`
    - `for`, `do`, `while`
- operators
    - `==` and `!=` for equality checks, typical`<` / `<=` etc.
    - `++` and `--`
- OOP
    - `class`, `new`, `this`, `super`, `extends`
    - `abstract`, `interface`
    - `instanceof`
    - `private`, `protected`, `public`
    - `static`
- Keywords
    - 61 of them, many above
    - `const` and `goto` are reserved but unused
    - also, `true` / `false` / `null` reserved, and sometimes `var` (contextual)
- Identifiers
    - begin with letters, `_`, or `$`
    - can continue with any of the above + digits
    - case-sensitive

> "Java supports three styles of comments"