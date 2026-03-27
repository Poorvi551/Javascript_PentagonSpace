# Javascript_PentagonSpace

* History of Javscript :

  * In 1995 javascript was developed by Brendan Eich.
  * He was working at Netscape Communication(Web Browser Company).
  * He named javascript firstly as MOCHA.
  * MOCHA -> livescript -> ECMA International(European Computer Manufacturer Association). -> ECMA script -> Javascript.

* Javascript :-

  * Javascript is used to add functionality for the web pages.
  * Javascript is a light-weight object based programming or scripting language used by several websites for scripting the webpages.
  * Javascript is a client-side(frontend) language.      Python(server-side)

* Features of Javascript:-

  * Javascript is a interpreted language.
  * Javascript is dynamically typed language.
  * JIT(Just In Time) is present.
  * Client side language.
  * Supports - cross platform.
  * Event - driven Architecture.

* Applications of Javascript:-

  * Javascript can be used for wide range of applications.
    
    1. Frontend development.
    2. Backend development using node.js
    3. Mobile App development using React native.
    4. Game development using libraries like Three.js, phaser.js(2D Games).
    5. Desktop App development using electron.js(vs code).
    6. Machine Learning using tensorflow.js

* Javascript Engine:-

  * Javascript Engine is responsible for executing javascript code.
  * Each and every browser will have javascript engine with different names such as chrome - V8, Edge - Chakra, Firefox - SpiderMonkey, Safari - JS Core.

  * Working of Javascript Engine:

    * Parser takes the javascript code and it generates AST.
    * AST - AST stands for Abstract Syntax Tree - It is a structured representation of a code.
    * Interpreter converts this AST it into a byte code(Intermediate or Instruction).
    * Compiler - Compiler takes byte code and converts it into a Machine code and produces output.

  * Javascript uses JIT(Just In Time) Compiler to optimize the process of code execution.

Ways of writing javascript code:

  * NOTE : There are two ways of writing javascript code.
     * Types are:

        1. Internal method
        2. External method

     1. Internal method:
        ________________________________________________________________________________________________________________
    
             <!DOCTYPE html>
             <html>
             <head>
                <meta>
                <title></title>
             </head>
             <body>
                <h1>Hello! welcome to javascript session</h1>
                <script>
                    console.log("Hello")
                </script>
             </body>
             </html>
        __________________________________________________________________________________________________________________

    2. External method :
    _______________________________________________________________________________________________________________________

    index.html
    
          <!DOCTYPE html>
             <html>
             <head>
                <meta>
                <title></title>
             </head>
             <body>
                <h1>Hello! welcome to javascript session</h1>
                <script src="index.js"></script>
             </body>
             </html>
  __________________________________________________________________________________________________________________________
  
    
  __________________________________________________________________________________________________________________________

   index.js
                  
                  console.log("Hello")
  __________________________________________________________________________________________________________________________

* NOTE : Javascript code should always be written before closing the body tag(</body>) at the  end of the html file because first HTML Elements and CSS Elements should be rendered before executing the javascript code.

* NOTE : We can write the script tag anywhere but we have to use keywords called async or defer, this method will work only in external method of writing javascript code.
  
  * ASYNC - Async will execute both HTML and Javascript code parallely.
  * DEFER - Defer will execute first HTML code than executes the javascript code.


* Output method :

  1. console.log() - prints the statement in the console
  2. alert() - alerts with one button as OK
  3. confirm() - alerts with two buttons as OK and cancel
  4. document.write() - prints the statement on the browser without any space.
  5. document.writeln() - prints the statement on the browser with one space.

* Tokens - Tokens are the smallest individual unit of javascript program.

  
