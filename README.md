![YouTube Thumbnail for Learning TypeScript Livestream with book cover and photo of Josh Goldberg and Jenn Junod](https://user-images.githubusercontent.com/77285384/213764058-afaee6da-2057-43a6-9e36-f5f5ee467997.png)

# Learning TypeScript w/ Josh Goldberg

✨Hello beaufitul human! ✨

[Jenn Junod](http://linktr.ee/jennjunod), host of "Teach Jenn Tech," teams up with [Josh Goldberg](https://www.joshuakgoldberg.com/), author of "Learning TypeScript," to offer you a deep dive into TypeScript essentials. From key language features to community happenings, this episode has something for everyone—whether you're a TypeScript novice or seasoned pro. 

### What's Inside
- **Core Concepts**: We demystify TypeScript, discussing interfaces, type aliases, and optional properties, complete with real-world examples.
- **Community Buzz**: Stay updated with upcoming TypeScript events and the challenges of live streaming.
- **Fun Stuff**: We manage to sprinkle in some video game and pet talk for good measure!

### Key Resources
- **Book**: [Learning TypeScript](https://www.oreilly.com/library/view/learning-typescript/9781098110321/)
- **Projects**: [Chapter Projects](https://www.learningtypescript.com/projects)
- **Summaries**: [Chapter Summaries](https://www.learningtypescript.com/from-javascript-to-typescript)
- **Livestream Recording Playlist**: [Recording Playlist](https://www.youtube.com/playlist?list=PLlbXwLyUGk1yObhssreew0DMQmQ8yC_iJ)

### Takeaways
- Know the key differences between interfaces and type aliases.
- Grasp how optional properties can make your TypeScript code more robust.

Don't miss out—like, share, and subscribe for a tech-loaded journey. See you next time! 🎉👩‍💻

\#TeachJennTech \#TypeScript \#LearningTypeScript \#TechTalks \#DevJourney





## Module/Chapter Breakdowns
### 1️⃣ From JavaScript to TypeScript
 [👀 Chapter 1 Recording](https://youtube.com/live/K710B5oMYAU?feature=share)

 [📝 The Typeinator Project](https://www.learningtypescript.com/from-javascript-to-typescript/the-typeinator/) 
 - If you're not a fan of classes, skip this project  😂


 Learning TypeScript's From JavaScript to TypeScript chapter covers the context for some of JavaScript's main weaknesses, where TypeScript comes into play, and how to get started with TypeScript:

A brief history of JavaScript
  - JavaScript's pitfalls: costly freedom, loose documentation, and weaker developer tooling
  - What TypeScript is: a programming language, a type checker, a compiler, and a language  service
  - TypeScript's advantages: freedom through restriction, precise documentation, and stronger developer tooling
  - Getting started writing TypeScript code on the TypeScript Playground and locally on your computer
  - What TypeScript is not: a remedy for bad code, extensions to JavaScript (mostly), slower than JavaScript, or finished evolving


### 2️⃣ The Type System 
[👀 Chapter 2 Recording](https://youtube.com/live/2XGpHFmgrAQ?feature=share)

 [📝 System of a Clown Project](https://www.learningtypescript.com/the-type-system/system-of-a-clown/)

Learning TypeScript's The Type System chapter covers how TypeScript's type system works at its core:
- What a "type" is and the primitive types recognized by TypeScript
- What a "type system" is and how TypeScript's type system understands code
- How type errors compare to syntax errors
- Inferred variable types and variable assignability
- Type annotations to explicitly declare variable types and avoid evolving any types
- Object member checking on type shapes
- ECMAScript module files' declaration scoping compared to script files


### 3️⃣ Unions and Literals
[👀 Chapter 3 Recording](https://youtube.com/live/7vUtd2JDU5Y?feature=share)

 [📝 Primitive Cooking Project](https://www.learningtypescript.com/unions-and-literals/primitive-cooking/)
  [📝 The Narrow Trail](https://www.learningtypescript.com/unions-and-literals/the-narrow-trail/)

 Learning TypeScript's Unions and Literals chapter covers union and literal types in TypeScript, along with how its type system can deduce more specific (narrower) types from how our code is structured:

- How union types represent values that could be one of two or more types
- Explicitly indicating union types with type annotations
- How type narrowing reduces the possible types of a value
- The difference between `const` variables with literal types and let variables with primitive types
- The "billion-dollar mistake" and how TypeScript handles strict null checking
- Using explicit `| undefined` to represent values that might not exist
- Implicit `| undefined` for unassigned variables
- Using type aliases to save typing long type unions repeatedly


 ###  4️⃣ Objects
[👀 Chapter 4 Recording](https://youtu.be/5m-VKKjzNJk)

 [📝 Various Lawyerings](https://www.learningtypescript.com/objects/various-lawyerings/)

  [📝 The Typer](https://www.learningtypescript.com/objects/the-typer/)

Learning TypeScript's Objects chapter expands your grasp of the TypeScript type system to be able to work with objects:

- How TypeScript interprets types from object type literals
- Describing object literal types, including nested and optional properties
- Declaring, inferring, and type narrowing with unions of object literal types
- Discriminated unions and discriminants
- Combining object types together with intersection types


 ### 5️⃣ Functions 
[👀 Chapter 5 Recording](https://youtu.be/W0fkrUicn6o)

 [📝 Secret Secrets](https://www.learningtypescript.com/functions/secret-secrets/)

  [📝 Structural Kitchen](https://www.learningtypescript.com/functions/structural-kitchen/)

 Learning TypeScript's Functions chapter shows how a function's parameters and return types can be inferred or explicitly declared in TypeScript:

- Declaring function parameter types with type annotations
- Declaring optional parameters, default values, and rest parameters to change type system behavior
- Declaring function return types with type annotations
- Describing functions that don't return a usable value with the `void` type
- Describing functions that don't return at all with the `never` type
- Declaring function types in type annotations
- Using function overloads to describe varying function call signatures


 ### 6️⃣ Arrays 
[👀 Chapter 6 Recording](https://youtu.be/E1UmLmq-bt0)

 [📝 Analyzing DNA](https://www.learningtypescript.com/arrays/analyzing-dna/)

  [📝 Text Processor](https://www.learningtypescript.com/arrays/text-processor/)

Learning TypeScript's Arrays chapter covers declaring arrays and retrieving their members:

- Declaring array types with `[]`
- Using parentheses to declare arrays of functions or union types
- How TypeScript understands array elements as the type of the array
- Working with `...` spreads and rests
- Declaring tuple types to represent fixed-size arrays
- Using type annotations or `as const` assertions to create tuples

### 7️⃣ Interfaces 
[👀 Chapter 7 Recording](https://youtu.be/U2szfBQjE3U)

 [📝 Vacation Planning](https://www.learningtypescript.com/interfaces/vacation-planning/)

  [📝 Playlist Soundness](https://www.learningtypescript.com/interfaces/playlist-soundness/)

 Learning TypeScript's Interfaces chapter covers how object types may be described by interfaces:

- Using interfaces instead of type aliases to declare object types
- Various interface property types: optional, read-only, function, and method
- Using index signatures for catchall object properties
- Reusing interfaces using nested interfaces and `extends` inheritance
- How interfaces with the same name can merge together


Josh Goldberg has given permission to use contents of his book and promotion of his work. He says hi 👋