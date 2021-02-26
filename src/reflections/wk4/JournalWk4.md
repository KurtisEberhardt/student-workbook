Day 1: 
1. What are some of the signs and causes of Callback Hell?
    One of the signs of Callback Hell is the pyramid shape of )} at the end of your code. The cause is when developers write their code to be read bottom to top when it's meant to be asynchronus. 

2. What does the asynchronous mean and how are callbacks involved?
    Asynchronous means "happening later" or "takes some time". Callbacks are just functions that take a second or two to produce a result.
3. Summarize the 3 ways to avoid / fix Callback Hell
    The three ways to avoid Callback Hell are to keep your code shallow, modularize your code, and to handle every single error that comes up. 
Day 2: 
1. What are the three states of a Promise?
    Pending, Resolved, and Rejected
2. How do promises seek to resolve the issues of "callback hell"?
    Promises solve callback hell by just making the code pause until it recieves a response from whatever it's trying to recieve data from. 
3. What is the difference between .then() and .catch()?
    .then() recieves successful calls, and .catch() recieves unsuccssful calls, or errors. 
Day 3: 
1. What is the purpose of Async/Await?
    Async basically dictates a function will return a promise, and await will make the asynced code to wait until it recieves the promise. 
2. What must you do in order to await a promise inside of a function?
    You must prepend the async keyword onto the function.
3. What are some of the primary benefits of Async/Await?
    Async and Await are much easier to read, allow for multiple in a series more easily, and allow for easier debugging. 
Day 4: 
1. What does REST stand for, and in simple terms what does it mean?
    REST stands for REpresentational State Transfer. It basically means that if you contact a RESTful API, you'll recieve a representation of the state requested. 
2. What does Stateless mean?
    Stateless means that the server doesn't remember anything about the user who uses the API.
3. What URL pattern is used when writing a RESTful API?
    a RESTful api uses .co/api/<whatever>