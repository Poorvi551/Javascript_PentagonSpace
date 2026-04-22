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

GEC Execution :

 * GEC - GEC stands for Global Execution Context.
 *  Whenever the javascript program is given to javascript Engine a new memory is created that memory is called Global Execution Context(GEC).

* GEC has 2 stages:

   1. Variable phase
   2. Function/Execution Phase
* GEC has 2 steps :

  1. Memory is created or allocated.
  2. Execution happens from top to bottom, left to right and by default all the values are assigned as undefined.

Typecasting :

* Converting one type of data into another type of data is called typecasting.

  * They are of 2 types :

     1. Implicit Typecasting
     2. Explicit Typecasting

  1. Implicit Typecasting -

     * Converting one type of data into another type of data internally or implicitly is called Implicit typecasting.
     *  Ex: console.log(1+3);

  2. Explicit Typecasting -

     * Converting one type of data into another type of data externally or explicitly is called Explicit typecasting.
     * There are 3 in-built methods. They are :
          1. Number()
          2. String()
          3. BigInt()

Inputs :

* Inputs are of 2 types :
     1. static inputs
     2. dynamic inputs

1. Static inputs :
 
      code : ex: var a=10;
                 var b=20;
                 console.log(a+b);
     
     * EX: source code : Assignment 3 folder in this repo.

2. Dynamic inputs :
 
      code : ex: var a=prompt("Enter a:");
                 var b=prompt("Enter b:");
                 console.log(a+b);  // a-> 10, b-> 20 o/p -> 1020     to overcome this use Number(prompt()) except subtract bcz subtract sign will defaultly convert it into number.
     
     * EX: source code : Assignment 3 folder in this repo.

Literals :

1. Primitive :-

    * They are Immutable.
    * They are object Dereferencing.

  i. String Literals:

   * They are Immutable.
   * They are object Dereferencing.

      1. " " - double quotes
      2. ' ' - single quotes
      3. ` ` - Backticks
            1. Template string
            2. String Interpolation
               * Ex : source code - stringliterals.html
   
       * NOTE - To print the the string with double quotes like("hello") we use '"hello"' - singel quotes, to print with single quotes like('hello') we use "'hello'" and to print with backticks like(`hi`) we can use either single quotes or double quotes("`hi`") or ('`hi`').
                 
        * String Methods :

          * Ex : source code - stringliterals.html
          * str.length - length of string
          * str.toLowerCase() - converts to lowercase
          * str.toUpperCase() - converts to uppercase
          * str.toLocaleLowerCase() - converts to lowercase
          * str.toLocaleUpperCase() - converts to uppercase
          * str.charAt(0) - prints letter at the index 0 if the space is not occupied returns blank
          * str.indexof(H) - prints index of the letter H
          * str.lastIndexOf(l) - prints from last index of the letter l where it finds the first l
          * str.slice()- prints the n-1 letter, 2 parameters (strat index, end index)
          * str.replace("H","R") - replace letter H to R.
          * str.startsWith("H") - returns boolean val( true/false) if present or not.
          * str.endsWith("o") - returns boolean val( true/false) if present or not.
          * str.trim() - removes the space at both start and end sides.
          * str.trimStart() - removes spcae at start
          * str.trimEnd() - removes spcae at end
          * str.concat(str2) - concatenates the 2 strings.
          * str.split("") - converts whole string to array.
            
     ii. Number:
     
      * They are Immutable.
      * They are object Dereferencing.
          
     iii. Boolean:

      * They are Immutable.
      * They are object Dereferencing.
        
     iv. BigInt:

      * They are Immutable.
      * They are object Dereferencing.
        
     v. Undefined:

     * They are Immutable.
     * They are object Dereferencing.
       
     vi. Null:

     * They are Immutable.
     * They are object Dereferencing.
      
