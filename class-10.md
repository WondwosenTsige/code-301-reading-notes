
### [Table of Contents](https://wondwosentsige.github.io/code-301-reading-notes/Home)

## Read 09

### The call stack

- At the most basic level, __a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation.__

- A call stack is a mechanism for an interpreter to keep track of what function is currently being run and what functions are called from within that function.

- *The call stack is primarily used for function invocation*. Since the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

- In summary, the key takeaways from the call stack are:

    1. It is single-threaded. Meaning it can only do one thing at a time.

    2. Code execution is synchronous.

    3. A function invocation creates a stack frame that occupies a temporary memory.

    4. It works as a LIFO — Last In, First Out data structure.

- #### Error messages

- JavaScript is not a compiled language.So our errors will happen at runtime, that means that we can only see whatever is wrong with the code after running it.

- The first thing that indicates something is wrong with our code is the one wich usually appears on the  console.

- __Most types of errors includes reference errors, syntac errors, range errors, and type errors__

- Being able to read error messages and practising debugging is one of the biggest weapons for a developer. By doing it frequently and with enough time we will notice a great decrease in the time we spend debugging those errors.





























..........................................................................................

__Attributions for the following Reference materials and their authors__


[Understanding the JavaScript Call Stack, by Charles Freeborn](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/)

[JavaScript error messages, BY Diogo Spinola](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

[What is refactoring?](https://www.agilealliance.org/glossary/refactoring/#q=~(infinite~false~filters~(postType~(~'page~'post~'aa_book~'aa_event_session~'aa_experience_report~'aa_glossary~'aa_research_paper~'aa_video)~tags~(~'refactoring))~searchTerm~'~sort~false~sortDirection~'asc~page~1))


[The Call Stack defined on MDN](https://developer.mozilla.org/en-US/docs/Glossary/Call_stack)








[>> NEXT (Read-11)](https://wondwosentsige.github.io/code-301-reading-notes/class-11)