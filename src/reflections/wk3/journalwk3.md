day 1: 
1. What problem does using exports solve?
    
    Export solves the previous issue of not being able to reference multiple .js files natively in 
    JavaScript. Before ES6, you would need an external library to allow you to do that. 

2. How does export differ from export default?
    
    Export will export any features declared earlier in the document. Export Default will export anything in the following class or function.


3. What is a benefit of using the Module System?
    
    The module system is very good for code that is reusable in multiple situations. It also helps preformance greatly. 

day 2: 
1. What is the purpose of Encapsulation?
    Encapsulation is made to control what the user can access at the top level of the application. By doing this, you can make it so the application can store more sensitive data deeper in the application, away from prying eyes. 

2. What were some of the problems with closures and the underscore prefix?
    The underscore prefix is troublesome because some new developers didn't know about the convention. Some senior developers also ignored convention based on a "I know what i'm doing" attitude

3. How do we create private variables in a ES6 Class? Why would you do this?

day 3:
1. What are the two common operations that we will set in the handler?
    The two common operations that will be set in that handler are "get" and "set" 
2. What do you have to make sure you are doing with every Get to insure the value does not become undefined?
    You need to make sure you define the property that is actually being accessed by "get". That way it is not undefined.

3. What are some of the benefits of the proxy object that we are using in our structure for applications?
    If you use a proxy object you can conceal the data of the given proxied object. 
day 4: 
1. What problems does the Observer Pattern seek to solve?
    The Observer Pattern seeks to solve the reoccuring issue of wanting to update specific parts of the page instead of the whole page. 
2. What are the three mechanisms of the observer pattern?
    The three mechanism of the Observer Pattern are subscribe, unsubscribe, and broadcast. 
3. Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.

This is done by storing a rotating door of values defined in the AppState in the ProxyState object, which you can then access to update the DOM as needed by using dot operators.