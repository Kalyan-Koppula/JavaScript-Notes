Javascript JS for short is a high level functional and object oriented dynamically typed all purpose programming language , which is mostly used(not limited) in web development.
## who , why and what versions
When defining JS , it includes two parts 
- the language features
		These are the features defined by the ECMA, explained below.
- the runtime
		The actual environment where the code runs in typically the browser, or the server runtime node/deno/bun.
Netscape ( now Mozilla ) developed the javascript originally and gave it ECMA for standardization. that why JS is formerly called ECMAscript.
Important versions are ES5 released in 2010 , and then ES6 released in 2015, from then its followed by an annual release.
> Note: ECMA only specified the features list to add in the specific version , it’s up to the run time to define the implementation in code that follows the released specification.

The methods like variables definitions , conditionals, loops , classes , are common across all the run times , but each run time might include its own specific methods and functions that are available.

Eg: Browser provides you with options like history, storage, cookies, and window to interact with the actual browser functionalities which will not be available on the node run time .
lll’y node provides you with input output streams, file system and more.

## Some basic example of js code.
A Js file ends with the extension .js. ex: `mycode.js`
```javascript
console.log(“Hello world”);
let a = 10;
if(a>1){
//do something
} else {
//do other thing
}
while (a>10) {
//keep doing this thing.
}
```


Prev—[[README]] 
Next—[[LexicalScope]]
