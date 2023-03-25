# ud-intellij-debugging
Java Debugging with IntelliJ From Udemy
## Pre-requisites

- **IDE**: Intellij Idea
- **Course URL**: https://www.udemy.com/course/java-debugging-with-intellij-idea/


## Authors

- [@bhushan2005](https://www.github.com/bhushan2005)


## Documentation




## FAQ

1. What are renderers and how can we update them?
- Renderer are the way the list elements are rendered in the variable space during debugging.
- By default if we have a list of objects then we need to click and open each and every
element to see the values of the fields. This can be time consuming.
- So renderer can help to print the expression in a user friendly way so that you do not have to expand each and
every element. But this is at expense of performance.
- Go to Settings. Search for Renderer.
- Add a renderer for say Person class. The expression can be String.format("Name: %s, Age: %d", person.getName(), person.getAge())
- You can click 'On-demand' so that the rendering will happen only if you click. Thus not causing performance
impact.