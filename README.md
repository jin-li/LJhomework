# LJhomework

## Introduction
This is a LaTeX template for homework writing, modified from hmcpset, which is an mathematics homework template in Harvey Mudd College.

## Features
An example:  
![eg](/pic/eg/eg-1.PNG)
- Insert head block automatically
- Problems are boxed
- A small black square block is added automatically at the end of solution
- Use "myminted" to insert codes for all kinds of languages  

*For more functions and usage, please refer to the full [eg.pdf](eg.pdf)*


## Usage
1. Put hmcpset.cls and ljhwh.tex in the same directory with your homework.tex file.
2. At thebeginning of your homework.tex, add
    > \input{ljhwh.tex}
3. To compile it, use "xelatex" so that Chinese characters can be supported. The command is
    > xelatex -shell-escape homework.tex  

    To be noted, if you use references or cross references, you may need execute this command sever times until there's no "undefined reference" warning.

<<<<<<< HEAD
=======
___
## Full Example <span id="full"> </span>
![eg-1](/pic/eg/eg-1.PNG)
![eg-2](/pic/eg/eg-2.PNG)
![eg-3](/pic/eg/eg-3.PNG)
![eg-4](/pic/eg/eg-4.PNG)
![eg-5](/pic/eg/eg-5.PNG)
![eg-6](/pic/eg/eg-6.PNG)
![eg-7](/pic/eg/eg-7.PNG)
![eg-8](/pic/eg/eg-8.PNG)
![eg-9](/pic/eg/eg-9.PNG)
>>>>>>> 5bcd95ec8473b0b1d7188451f82fcffed1974bca
