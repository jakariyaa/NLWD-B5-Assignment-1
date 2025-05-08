# B5-Assignment-1

### How does TypeScript help in improving code quality and project maintainability?

TypeScript is a tool that helps developers write better and cleaner code. It works on top of JavaScript and gives extra help while coding.

1. Finds Mistakes Early
   TypeScript can catch mistakes before the code runs. This saves time and helps avoid bugs.

2. Uses Types for Safety
   Developers can tell TypeScript what kind of data they expect. This is called a type. Types make sure the wrong kind of data is not used. For example: let name: string = "Alice";
   Now, here name variable must always be a string.

3. Good for Big Projects
   In big teams, many people work on the same codebase. TypeScript helps them understand each other’s code better. It shows the developer what each part of the code is supposed to do.

4. Smarter Suggestions
   Code editors give hints while typing. With TypeScript, these hints are smarter and more helpful because the editor knows the types. It boasts productivity.

5. Easier to Refactor
   When someone looks at the code after a long time, TypeScript makes it easier to remember how things work. This helps when the code needs to be updated or fixed at later time.

### What is the use of enums in TypeScript? Provide an example of a numeric and string enum.

Enums in TypeScript are used to give names to a set of related values (such as week, direction etc). They make code easier to read, understand and manage.

Instead of using plain numbers or strings, enums helps us use meaningful names. Why should we use enums?

- To avoid magic numbers or strings in code
- To group related values
- To make code safer and cleaner

**Numeric Enum Example**

```
enum Direction {
  North,   // 0
  East,    // 1
  South,   // 2
  West     // 3
}

let move = Direction.East;
```

In the above example, Direction.East means 1.

**String Enum Example**

```
enum Status {
  Success = "SUCCESS",
  Error = "ERROR",
  Loading = "LOADING"
}

let result = Status.Success;
```

In the above example, Status.Success means "SUCCESS".
