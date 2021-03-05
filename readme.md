# Using naming conventions

### Self-explanatory

A name must reveal its intention so everyone can understand and change the code easily. For example, the names
"d" or "str" do not reveal anything; however the names "daysToExpire" or "inputText" do reveal their intention clearly. Note that, if a name
requires a comment to describe itself, then the name is not self-explanatory.

### Meaningful distinction

If names must be different, then they should also mean something different. For example, the names "a1" and "a2" are meaningless distinction; and the names "source" and "destination" are meaningful distinction.

### Pronounceable

Names should be pronounceable as naturally as spoken language because we are humans - very good at words.
For example, which name can you pronounce and remember easily: "genStamp" or "generationTimestamp"?

- Class and interface names should be nouns, starting with an uppercase letter. Student, Car, Rectangle, Painter etc
- Variable names should be verbs, starting with a lowercase letter. run, start, stop, execute etc.
- Constant names should have all UPPERCASE letters and words are separated by underscores. MAX_SIZE, MIN_WIDTH, MIN_HEIGHT
- Using camelCase notation for names. StudentManager, CarController, numberOfStudents, runAnalysis etc.

Source of the tutorial: https://www.codejava.net/coding/10-java-core-best-practices-every-java-programmer-should-know#NamingConvention
Java code conventions: https://www.oracle.com/technetwork/java/codeconventions-150003.pdf

Convention from Sun java

- A file consists of sections that should be separated by blank lines and an optional comment identifying each section
- Files longer than 2000 lines are cumbersome and should be avoided
- Wrapping Lines
  -- Break after a comma
  -- Break before an operator
  -- Prefer higher-level breaks to lower-level breaks
  -- Align the new line with the beginning of the expression at the same level on the previous line
  -- If the above rules to conusing code or to code that's squished up aginst the right margin, just indent 8 spaces instead

### Enum

Enums are classes and should follow the conventions for classes. Instances of an enum are constants and should follow the conventions for constants. So

```
enum Fruit {APPLE, ORANGE, BANANA, PEAR};
```

There is no reason for writing FruitEnum any more than FruitClass. You are just wasting four (or five) characters that add no information
