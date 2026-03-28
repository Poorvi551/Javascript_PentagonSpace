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
* Keywords are predefined reserved words which have its own meaning.
* Identifiers - Identifiers are the name given to the javascript program.
* Literals - Literals are the values used in javascript program.

Reserved Words:

1. Abstract
2. Boolean
3. Break
4. Byte
5. Case
6. Catch
7. Char
8. Class
9. Const
10. Continue
11. Debugger
12. Default
13. Delete
14. Do
15. Double
16. Else
17. Enum
18. Export
19. Extends
20. False
21. Final
22. Finally
23. Float
24. For
25. Function
26. Goto
27. If
28. implements
29. Import
30. In
31. Instanceof
32. Int
33. Interface
34. Long
35. Native
36. New
37. Null
38. Package
39. Private
40. Protected
41. Public
42. Return
43. Short
44. Static
45. Super
46. Switch
47. Synchronized
48. This
49. Throw
50. Throws
51. Transient
52. True
53. Try
54. Typeof
55. Var
56. Void
57. Volatile
58. While
59. With

* Literals -

  They are of two types-
  
    1. Primitive Datatype  - Immutable(Object- Dereferencing) -> number,string,boolean,null,undefined,bigInt
    2. Non Primitive Datatype - Mutable(Object- Referencing) -> functions, arrays(filter,map,reduce), object(date,time,math)

Variable :-

  * Variable is a named memory location which is used to store some data or value and that can be changed n number of times during execution.

  * There are 3 types  of variables :

       1. Var -> global scope
       2. let   ---\ Function scope, block scope,
       3. const ---/ script scope, local scope

 * There are 4 operations to be performed :

    1. Declaration
    2. Declaration and Initialization
    3. Re-Initialization
    4. Re-Declaration

 1. Declaration :

    * var - possible
    * let - possible
    * const - not possible

 2. Declaration and Initialization :

    * var - possible
    * let - possible
    * const - possible

 3. Re-Initialization :

    * var - possible
    * let - possible
    * const - not possible
       
 4. Re-Declaration :

    * var - possible
    * let - not possible
    * const - not possible

* Hoisting :

* Utilising the variable before the initialization line is called hoisting.

* Ex : console.log(a)
       var a = 10;

* var -> possible - o/p -> undefined
* let, const -> Referrence Error -> TDz - Temporal Dead Zone

* Temporal Dead Zone :

   * The time gap between utilization and initialization line is called Temporal Dead Zone.

  
