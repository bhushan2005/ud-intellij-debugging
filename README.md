# ud-intellij-debugging
Java Debugging with IntelliJ From Udemy
## Pre-requisites

- **IDE**: Intellij Idea
- **Course URL**: https://www.udemy.com/course/java-debugging-with-intellij-idea/


## Authors

- [@bhushan2005](https://www.github.com/bhushan2005)


## Documentation

File under consideration: DebugPerson.java
Watch placed for personList and personMap


## FAQ

1. What is the use of filter?
- In case during debugging you have an array or map with huge number of elements, then 
it could be difficult to see the values of every item.
- In such cases, you can use Filter which can filter the list or map to the specific 
condition.

2. How to add a filter?
- This can be done in variable view or you can add the variable to the watch and then add the filter there.
- Right click on list and select 'Filter' and give the condition as: this.getAge() > 40
- If its a map, then you can use this.getKey().equals(2)