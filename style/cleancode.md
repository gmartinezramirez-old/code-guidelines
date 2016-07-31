# Clean Code Textbook

## Names

Name are everywhere, variables, functions, arguments, classes, packages, source files and directories(jar, war and ear file ...), follow some rules to improve the readability of your code.

 - rule 1 Use Intention-revealing Name:

     choosing good name takes time but save more than it takes, a name should tell the reader why it exists, what it does, and how it is used, which makes it easier to understand and change code.

 - rule 2 Avoid Disinformation:

     keep words being hnonest to our intent meaning and avoid leaving false clues taht obscure the meaning of the code.

 - rule 3 Make Meaningful Distinctions:

     make different name if and only if they mean diferent things.　noninformative number-series name provid no clue to the author's intent and noise words is redundant and meaningless distinction.

 - ruel 4 Use Pronounceable Names:

     programming is a social activity, and programmer could discuss well with pronounceable name as human is good at words with concepts.

 - rule 5 Use Seachable Names:

     the name length corresponds to the size of its scope.

 - rule 6 Avoid Encoding:

     Hungarian Notation is hard to read and change and might mislead the reader. Member Prefixes becomes unseen clutter while the name of classes and functions is small enough. Interfaces and Implementations, prefer encoding the implementation name rather than the interface name.

 - rule 7 Avoid Mental Mapping:

     Clarity is king, professionals use their powers for good and write code that others can understand while smart programmers sometime like to show off their smarts by demonstrating their mental juggling abilities.

 - rule 8 Class Names:

     classes and objects should have noun or noun phrase name and should not be a verb. Prefer 'Customer', 'WikiPag'e, 'Account' or 'AddressParser'  avoid 'Manager', 'Processor', 'Data' or 'Info'.

 - rule 9 Methods Names:

     methods should have verb or verb phrase names. Accessors, mutators and predicates should be name for their value and prefixed with get, set and is according to java bean standard. User static methods with name that describe the argment for private overloaded constructors.

 - rule 10 Donnot Be  Cute:

      choose clarity over entertainment value, say what you mean and mean what you say.

 - rule 11 Pick One Word per Concept:

     A consistent lexicon is a great boon to the programmers who must use your code. Pick one word for on abstract concept and stick on it.

 - rule 12 Donnot Pun:

     Use the same word for two different purposes is essentially a pun, don't do that.

 - rule 13 Use Solution Domain Names:

     Choosing technical names for technical things is usually the most appropriate course as code readers wil lbe programmers. Go ahead and use computeer's science terms, algorithm names, pattern names, math names, and so forth.

 - rule 14 Use Problem Domain Names:

     Use the names from the problem domain if and only if there is no "programmer-eese" for what we are doing.

 - rule 15 Add Meaningful Context:

     place names in context for your reader by enclosing them in well-named classes, functions, or namespaces.

 - rule 16 Donnot Add Gratuitous Context:

     Shorter names are generally better than longer ones, so long as they are clear.


## Functions

Functions are the first line of organization in any program, make it easy to read and understand.

* Small
* Do One Thing
* One Level of Abstraction per Function
* Switch Statements
* Use Descriptive Names
* Function Arguments
* Have No Side Effects
* Command Query Seperation
* Prefer Exception to Returning Error Code
* Don't Repeat Yourself
* Structured Programming
* How Do You Write Function Like This

## Comments

* Comments Do Not Make Up for Bad Code
* Explain Yourself in Code
* Good Comments
* Bad Comments

## Formatting

* The Purpose of Formatting
* Vertical Formatting
* Horizontal Formatting
* Team Rule
* Uncle Bob's Formatting Rules

## Objects and Data Structures

* Data Abstraction
* Data/Object Anti-Symmetry
* The Law of Demeter
* Data Transfer Objects

## Error Handleing

* Use Exception Rather Than Return Codes
* Write Your Try-Catch-Finally Statement First
* Use Unchecked Exception
* Provide Context with Exception
* Define Exception Classes in Terms of a Caller's Needs
* Don't Return Null
* Don't Pass Null

## Boundaries

## Unit Tests

## Classes

<b>Systems</b>

<b>Emergence</b>

<b>Concurrency</b>

<b>Successive Refinement</b>

<b>JUnit Internals</b>

<b>Refactoring SerialDate</b>

<b>Smell and Heuristics</b>
