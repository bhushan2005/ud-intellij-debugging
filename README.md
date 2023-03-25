# ud-intellij-debugging
Java Debugging with IntelliJ From Udemy
## Pre-requisites

- **IDE**: Intellij Idea
- **Course URL**: https://www.udemy.com/course/java-debugging-with-intellij-idea/


## Authors

- [@bhushan2005](https://www.github.com/bhushan2005)


## Documentation

File under consideration: DebugPerson.java
Add breakpoint at System.out.println("personList:" + personList);



## FAQ

1. What is a class level watch?
- Cannot think of a use case for this yet.
- Its used to add a watch (expression) to all the items of a list.
- Create a breakpoint after the line where arraylist is created.
- Then in the variables space below, right click on the first item and Add Class level watch. For
eg: this.getAge()>20.
- This watch will be added and evaluated to all the items of the list. This will be displayed in the variable space.
- If the watch is no longer required, then right click the watch expression and select 'Remove Watch'