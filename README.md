# LJhomework

## Introduction
This is a LaTeX template for homework writing, modified from hmcpset, which is an mathematics homework template in Harvey Mudd College.

## Features
An example:  
![eg](eg.PNG)
- Insert head block automatically
- Problems are boxed
- A small black square block is added automatically at the end of solution
- Use "myminted" to insert codes for all kinds of languages

## Usage
1. Put hmcpset.cls and ljhwh.tex in the same directory with your homework.tex file.
2. At thebeginning of your homework.tex, add
    > \input{ljhwh.tex}
3. To compile it, use "xelatex" so that Chinese characters can be supported. The command is
    > xelatex -shell-escape homework.tex
