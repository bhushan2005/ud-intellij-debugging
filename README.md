# ud-intellij-debugging
Java Debugging with IntelliJ From Udemy
## Pre-requisites

- **IDE**: Intellij Idea
- **Course URL**: https://www.udemy.com/course/java-debugging-with-intellij-idea/


## Authors

- [@bhushan2005](https://www.github.com/bhushan2005)


## Documentation



## FAQ

1. What is Smart Step Into?
- If you have setup breakpoint and then debug program, then execution will halt at the breakpoint.
- Then if you do Step Into, then the execution will go step by step from left to right for all the function calls on the line.
- Instead, if you want to skip some function calls on the line and directly step into function call which is in the middle, then use 'Smart Step Into'
- This option is present in Run > Debugging Actions > Smart Step Into.

2. What is 'Run to Cursor' and 'Force run to cursor'?
- If you have setup breakpoint and then debug program, then execution will halt at the breakpoint.
- Then if you want to move to a location which does not have breakpoint, then instead of doing multiple step overs, you can place the cursor at the start of that line and click 'Run to cursor'
- This will bring the control to the start of that line and pause.
- The above method will also halt if there are any breakpoints on the way.
- If you do not want that behaviour, then you 'Force run to cursor'. This will skip any intermediate breakpoints.