# Writing Hello World in console using node.js:
Write Hello World in node.js is quiet easy,
in my code, i write console.log() method,

# Function of console.log() method.

console.log() method used for printing some text in the console.

example:

when i write code like this:

`console.log('Hello ....');`

-Save it somewhere with .js extension.
-Run CMD.
-And change the directory using "cd" command to your local project folder.
-And type command like `'node YOURFILENAME.js'`.
-Press enter.
-You will see `"Hello ...."` in your console.

# Writing with string variable

You can change the words with string too.

ex:
```
var name = Rainer;

console.log('Hello ' + name);
```

and run cmd again,
you will see "Hello Rainer" in your console.

Thats's all for the `console.log()` method.

Thanks for reviewing.

# How to run my code:

i'll show you how to run my code in your computer using command prompt.

1. You have to install node.js first. if you haven't, go to [Here](https://nodejs.org/en/)
2. After you done installing node.js, Create a folder in your desktop,
3. Copy the directory address and open cmd,
4. Type `cd ` and the directory you've copied.
5. Type `npm install helloworldnodejs` to install my node module.
6. After the download is finished, create a file named hello.js in your root folder.
7. Write the code below, and save it:
```
var hello = require('helloworldnodejs');

hello.printMsg();
```
this code function is for call the printMsg method in my module.
8. Back to your CMD, type `node hello.js` , it'll run the code.
9. You will see the hello world words

Thats all how to run my code..
Thanks

# +++++++++++++++++++++++++++++++++++++++

Regards.
Rainer A. Regan.
New Developer in the future :D.
