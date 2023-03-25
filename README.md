# ud-intellij-debugging
Java Debugging with IntelliJ From Udemy
## Pre-requisites

- **IDE**: Intellij Idea
- **Course URL**: https://www.udemy.com/course/java-debugging-with-intellij-idea/


## Authors

- [@bhushan2005](https://www.github.com/bhushan2005)


## Documentation

File under consideration: DebugPersonDetailsIteration.java
Add action breakpoint at Person person = personList.get(i);



## FAQ

1. What is the use of action breakpoint?
- It is similar to logger statement except that we are not changing the code. 
- An action breakpoint is added by pressing shift and clicking on the left gutter of the code.
- It displays a yellow dot instead of red dot.
- The execution doesn't halt at the action breakpoint. But it just prints that it has reached breakpoint.
- You can also evaluate and log any expression for action breakpoint. This is done by using 'Evaluate and Log' field in 
the breakpoint dialog "personList.get(i).getName()"
- You can uncheck 'Breakpoint hit' checkbox if you think that you don't need the default text.
- In 'View Breakpoints' this appears as Java Line Breakpoint.