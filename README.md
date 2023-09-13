# Today-I-Learned

A collection of concise write-ups on small things I learn day to day across a variety of languages and technologies. These are things that don't really warrant a full blog post.

_1 TIL and counting..._

---
### ASP.NET
- [Dependency Injection in ASP.NET Core](asp.net/dependency-injection.md)
- ---

 ### Today I learned about Dependency Injections
 I learned that Dependency Injections are used to separate the creation of dependencies from the code that's 
 going to use it. It allows our code to be more tangible so that our code doesn’t heavily 
 rely on certain components. I also learned that they are used to improve the quality our code and 
 increase usability in our tests. They can also be bad for our code because it can make it more complex in the long 
 because of the sheer number of classes that can be created with DI. For example, this about it like this. Lets say I have 2 two students
 and I wanted both of them write me a essay except I only told person 2 what to write the essay about
 person 1 has no idea what I want him to write. Person 2 is now a good example of dependency injection. His essay object
 now has informtion passed into its contructor whereas person 1 s contructor will remain default.




---
## Inspiration
Inspired by [jbranchaud/til](https://github.com/jbranchaud/til).

## Contributing
The best way you can contribute is to support the idea of keeping track of things you learned. Just create a public repo and start writing and sharing notes. This is way better than keeping them to yourself.
