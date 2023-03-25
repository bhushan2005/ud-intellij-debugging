# ud-intellij-debugging
Java Debugging with IntelliJ From Udemy
## Pre-requisites

- **IDE**: Intellij Idea
- **Course URL**: https://www.udemy.com/course/java-debugging-with-intellij-idea/


## Authors

- [@bhushan2005](https://www.github.com/bhushan2005)


## Documentation

File under consideration: DebugPersonDetailsIteration.java



## FAQ

1. What is the use of exceptional breakpoint?
- It is used to add a breakpoint at runtime where the exception has occured and helps to see the 
program state at that instant. It encompasses the entire program.
- This is added by going to Run > View Breakpoints. Add + Java Exception Breakpoint
- Select the exception class. For eg: ClassCastException.
- You can also use the existing 'Any Java Exception' and this will halt the program at runtime
whenever any exception occurs.