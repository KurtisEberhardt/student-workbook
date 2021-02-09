day one: 
1. What is Scope ?
    
    Scope means where in the code a variable can be used. var for example is globally scoped which means the data it holds can be accessed anywhere
2. What is Hoisting ?
    
    Hoisting allows you to move variables and function declarations to the top of their scope before the 
    code executed. This results in the code result being undefined when it is executed. 

3. In what cases might you use let vs const vs var?
    
    Let is preferable to const and var for most general situations. Const would be used when the data a variable holds can't be changed or shouldn't be changed. 

day two: 
1. What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?
    The three ways to write a function are: 
        function xyz(abc){}
        let dgf = function(xyz) {}
        let lmo = (stuff) => {}


2. What is the difference between Parameters and Arguments?
    Parameters are placeholders in functions that basically declare that you need to pass data into the function. Arguments are the data passed into the function itself. 

3. What are higher order functions? Can you provide an example?
    A higher order function is a function that takes an arguement or returns a function itself. 
    function abc(xyz){
        function dgf(lmo)
    }