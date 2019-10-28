# ASSESSMENT 4: REACT ASSESSMENT
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.  

1a. Indicate which of the following statements about React are false:

- React is a modern, efficient answer to complex UI applications (true/false)
- React will only render on the server using Node.js (true/false)
- React is a full stack framework for modern web applications (true/false)
- React is a flexible library that plays the role of V in an MVC framework (true/false)
- You should always update a component's state directly using this.state (true/false)
- React is made up of encapsulated components that manage their own state (true/false)
- React components render HTML (true/false)

1b. Add an interesting TRUE fact about React to the list.

2. What are "smart" and "dumb" components? Explain the difference and also add why we bother to make the distinction between them.

  Your answer: dumb components are used once and cant be called again. Smart componenets
  on the otherhand, smart conponents hold state and can be reussed and reassigned.

  Researched answer:Dumb components are also called ‘presentational’ 
  components because their only responsibility is to present something to the DOM. 
  ex. <h1> hello world </h1> 
  Smart components (or container components) on the other hand have a different responsibility.
  Because they have the burden of being smart, they are the ones that keep track of state and care about how the app works.



3. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?

  Your answer: Add the react template.

  Researched answer: he add subcommand installs a module in the current project. You can specify more than
  one module by separating them with a space. Here, we are installing react and react-dom .
  Yarn will now fetch the modules including their dependencies and install them.



4. What is the difference between component state and props? Your answer should include a short explanation of both.

  Your answer: state only applies to the destuctering 
  within the parent file. When you use props, you are transferring information from child to parent. 

  Researched answer:the difference is that state is something like attributes in OOP : it's something local to a 
  class (component), used to better describe it. Props are like parameters - they are 
  passed to a component from the caller of a component (the parent) : as if you called a function with certain parameters.



5. How would you explain state to a friend who doesn't know code?

  Your answer: State lies within the begining of ones code; is a brief statement that assigns something a value which
  then later, can be called again with the same value or you have the ability to setState to a new value 
  and then recall that or reset it again later. 
