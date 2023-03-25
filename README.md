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

1. What is the use of conditional breakpoint?
- In case you have a list with large number of elements and there are some suspect elements
for which you need to apply breakpoint and observe the code, then it will be difficult to use a 
normal breakpoint as this will halt the code on every iteration.
- In this case, conditional breakpoint can be used.
- Right click the normal breakpoint created and put an expression in Conditional field. For eg:
  !(personList.get(i) instanceof Person). This will halt the execution when the personList element fails the condition.
- You can then do step into or also you can directly evaluate expression for the suspect element.