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

1. What is a Watch and how to add it?
- When the code is halted at breakpoint, then right click any variable and select "Add to Watches".
- Instead of just outputting a variable you can also write expression in the watch window. Eg: person.getAge()>30. This will show if its true or false.

2. What is 'Evaluate Expression'?
- This is used to check the value of some variable when the program has paused execution due to breakpoint.
- Right click on the variable and choose 'Evaluate Expression'.
- There too, you can call any getter method on the variable. For eg: person.getName().

3. When do you use Watch and Evaluate Expressions?
- You use watch if you want to monitor some variable or expression throughout the program execution.
- You use 'Evauate Expressions' when you want to check the value of a variable or expression just oncel