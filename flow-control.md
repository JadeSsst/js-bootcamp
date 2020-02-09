### Eloquent JavaScript - Asynchronous Programming
- In a synchronous programming model, things happen one at a time.  
- An asynchronous model allows multiple things to happen at the same time.  
- Asynchronous programming makes it possible to express waiting for long-running actions without freezing the program during these actions.   
- A thread is another running program whose execution may be interleaved with other programs by the operating system

- callback:  functions that are called when the actions complete  
- promises:  objects that represent actions that might complete in the future  
- async functions: which allow you to write an asynchronous program as if it were synchronous

### You Don't Know JS - Callbacks 
events heten ook wel async functions invocations

switch back and forth between two or more tasks in rapid succession, simultaneously progressing on each task in tiny, fast little chunks.  
dit is eigenlijk wat er geberut bij async evented concurrency

- Callbacks are the fundamental unit of asynchrony in JS.  

### The Coding Train - Promises
- callback makes sense voor een event (dus bijv mouseclick)  
- promise is een object  
- fetch function supports promises 

1. A “producing code” that does something and takes time. For instance, some code that loads the data over a network. That’s a “singer”.  
2. A “consuming code” that wants the result of the “producing code” once it’s ready. Many functions may need that result. These are the “fans”.  
3. A promise is a special JavaScript object that links the “producing code” and the “consuming code” together.  

new Promise(executor);  
new Promise(function(resolve, reject) { ... });  

verschillende statussen  
1. pending --> wachtende om data terug te krijgen van api  
2. fulfilled --> succesvol opgelost  
3. rejected --> een error is voorgekomen

JavaScript can send network requests to the server and load new information whenever is needed.  
Dit wordt vaak gedaan met fetch().  
**syntax**  
_let promise = fetch(url, [options])_

then() --> is een fucntie die een functie terugkrijgt om te execturen als ie fulfulled is  
catch() --> is een functie die functie terugkrijgt om te executeren als ie rejected is

### Fun Fun Function - Async Await
>The await operator is used to wait for a Promise. It can only be used inside an async function.

- The word “async” before a function means one simple thing: a function always returns a promise. Other values are wrapped in a resolved promise automatically.  
- The keyword await makes JavaScript wait until that promise settles and returns its result.

async/await is a type of promise.  
 Promises in JavaScript are objects that can have multiple states. Promises do this because sometimes what we ask for isn't available immediately, and we'll need to be able to detect what state it is in.
 
 .then() --> returns the resolution of your promise. 
