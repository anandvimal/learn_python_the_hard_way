# learn_python_the_hard_way

# ex1:

the keyword # makes makes a comment.

# ex2:
'#' is called pound and is single line comment.

for multiple lines start each line with #.

# ex3:
mod -> % (not percentage)
also this syntax works:
print "hens", 2+2, 2<3, (9+1)/7, 4%2
gives: hens 4 True 1 0

also if one of number is in floats eg 1.0 or 1.11 then whole calculation is done in floats. other wise its in integers.

order of operations: PEMDAS -> parentheses exponents multiplication division addition

# ex4&5:

learn about string formatting here:
https://docs.python.org/2/tutorial/inputoutput.html#fancier-output-formatting

difference between %s and %r:
http://stackoverflow.com/questions/1436703/difference-between-str-and-repr-in-python

# ex10:

ESCAPE Sequences

ESCAPE :	WHAT IT DOES.
```
\\	Backslash (\)
\'	Single-quote (')
\"	Double-quote (")
\a	ASCII bell (BEL)
\b	ASCII backspace (BS)
\f	ASCII formfeed (FF)
\n	ASCII linefeed (LF)
\N{name} :	Character named name in the Unicode database (Unicode only)
\r	Carriage Return (CR)
\t	Horizontal Tab (TAB)
\uxxxx :	Character with 16-bit hex value xxxx (Unicode only)
\Uxxxxxxxx :	Character with 32-bit hex value xxxxxxxx (Unicode only)
\v :	ASCII vertical tab (VT)
\ooo :	Character with octal value ooo
\xhh :	Character with hex value hh
```

# ex11:

ask inputs with : raw_input()
for example:

```
print "Enter your name:"
name = raw_input()
```

avoid using input() instead use raw_input()

# ex12


# ex15

get a filename in arguments
and then open a file like this:

```
txt = open(filename)

#to print the file do:
print txt.read()

```
