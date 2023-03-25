# ud-intellij-debugging
Java Debugging with IntelliJ From Udemy
## Pre-requisites

- **IDE**: Intellij Idea
- **Course URL**: https://www.udemy.com/course/java-debugging-with-intellij-idea/


## Authors

- [@bhushan2005](https://www.github.com/bhushan2005)


## Documentation

File: DebugFactorial
Place breakpoint at CalculatorUtil.factorial -> int result = 1;


## FAQ

1. What is the use of a drop frame?
- Drop frame is used to rewind back the call stack to a previous state.
- This is done by setting a breakpoint in the code and debugging it.
- When the control reaches breakpoint there could be multiple stack frames in the below left
- You can select a previous frame and select drop frame.
- This will drop all the frames from that point onwards and execution
will resume from that same point (it will rewind). 
- The values will also be set of that previous stack frame.
- This option is called 'Reset Frame' in newer versions of IntelliJ.