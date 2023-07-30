# Compiler-Design-lex-yacc
Lex and Yacc Programming for compiler Design

CMD Commands to Compile and Run. 

Lex file : file.l
$ lex file.l
$ ./a.out

Lex file : file.l 
Yacc file : file.y
$ lex file.l
$ yacc -d file.y
$ cc lex.yy.c yy.tab.c 
$ ./a.out

