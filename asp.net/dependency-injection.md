### Dependency Injection in an ASP.NET Core App


 ### Today I learned about Dependency Injections
 I learned that Dependency Injections are used to separate the creation of dependencies from the code that's 
 going to use it. It allows our code to be more tangible so that our code doesn�t heavily 
 rely on certain components.
 
 I also learned that they are used to improve the quality our code and 
 increase usability in our tests. They can also be bad for our code because it can make it more complex in the long 
 because of the sheer number of classes that can be created with DI. 
 
 
 For example, this about it like this. Lets say I have 2 two students
 and I wanted both of them write me a essay except I only told person 2 what to write the essay about,
 person 1 has no idea what I want him to write. Person 2 is now a good example of dependency injection, person 2 isnt using his own direct knowledge to write his essay
 information was passed into him from a outside source. Whereas person 1 is directly using his own ideas to create his essay, he recieves no outside info.