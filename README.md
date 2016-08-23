# haskell-general

Collection of concepts/ideas/terminology that I learn about haskell everyday!

### Algebraic Data Types
algebra = set of objects + operations on those objects that create new objects. In programming, the objects are data types (Int, Bool, String, etc) and the operations used to combine them are:
- multiplication: `data Point = Point Int Int` where both Ints are required to create the new data type `Point`
- addition: `data Person = Person String | Person Int` where a Person is represented by either a String or an Int, but not both!

### Point-free Style
Refers to a style of programming where we don't write the function arguments on both sides of the function definition. This style is prefered since it's more common to write functions in terms of other functions (function composition) and it looks more compact this way without the arguments. (The composition operator `.` has nothing to do with this name!)

### Referential Transparency
Property of programs, it means we can substitute the right-hand side of a function (function definition) with the left (function name) anywhere in the program and it will always evaluate the same.
