# ud-intellij-debugging
Java Debugging with IntelliJ From Udemy
## Pre-requisites

- **IDE**: Intellij Idea
- **Course URL**: https://www.udemy.com/course/java-debugging-with-intellij-idea/


## Authors

- [@bhushan2005](https://www.github.com/bhushan2005)


## Documentation

File: DebugStreamAndLambda
Place breakpoint at stream.of(..) line.


## FAQ

1. What are features provided for debugging streams and lambdas?
- If you place a breakpoint on a code with Stream.of... then Intellij will ask you
to which lambda do you want to add the breakpoint. Any specific or all.
- Then when you run the debug, it will halt at that lambda and show the value in the below variable space.
- You can click on "Trace Current Stream Chain" to see all the conversions and filtering in a
graphical view.