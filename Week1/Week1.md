<h1 align="center">:pushpin: Introduction to programming & Javascript - Week 1: Tuesday, July 19th, 2022</h1>

<h2> 1. Create an explanation about Interpreted And Compiled Programming Languages</h2>

<h3>- Interpreted Programming Languages</h3>
    
    Is the code that is ejecute line for line and it doesn't need compile with a compilator. 
    The computer is able to reed and ejecute the instructions. But for undestand the instruction, the computer needs a parser. 
    The parser reads the instruccions line for line and the ejecute it, so this process is late. 
    The interpreted Programming Languages is very tardy. Examples: JavaScript, Phyton, Ruby.

<h3>- Compiled Programming Languages</h3>

    Is a programming language whose implementations are typically compilers 
    (translators that generate machine code from source code) and not interpreters 
    (step-by-step executors of source code, where no translation is performed on pre-execution). 
    Converts code to binaries that are read by the operating system. Examples: C C#, GO.

<h2>2. Is Java compiled or interpreted, or both?</h2>

    Java is both a compiled and an interpreted language because its source code is first compiled into a binary byte-code. 
    This byte-code runs on the Java Virtual Machine (JVM), which is usually a software-based interpreter. 
    The use of compiled byte-code allows the interpreter (the virtual machine) to be small and efficient (and nearly as
    fast as the CPU running native, compiled code). In addition, this byte-code gives Java its portability: it will 
    run on any JVM that is correctly implemented, regardless of computer hardware or software configuration. 
    Most Web browsers (such as Microsoft Internet Explorer or Netscape Communicator) contain a JVM to run Java applets.
<div align="center"><img src="https://finematics.com/wp-content/uploads/2020/06/compiled-vs-interpreted-java-1024x479.png" with="200px" height="200px" /></div>

<h2>3. Pseudocode currency converter</h2>
<p>Definition the algorithm that will be used to convert dollars (USD) to bitcoin (BTC)</p>

`Pseudocode`
    
    Starting point: START
    Amount(input): <-- READ the amount
    ConvertedValue (output): GET the bitcoin amount from (https://www.coindesk.com/price/bitcoin/)
    Result: <-- Amount * ConvertedValue 
    PRINT Result
    END
