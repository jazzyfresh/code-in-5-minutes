# code in 5 minutes
learn to code in 5 minutes!


what is code?
-------------


when most people say code, they're thinking of programming languages, designed by humans
for the purpose of easily running operations on turing complete machines, usually built with electrical hardware.

um, what?

okay, i'll back up. a code is any symbol that represents a concept. code can be lots of things.
code can be cryptographic messages communicated between a client and a receiver. like morse code.
human language is a kind of code, where sentences have semantic meaning, derived by parsing the grammatical
structure of the words and their semantic meaning.

```
the orange fox jumped over the brown cow

the      orange     fox   jumped    ...
article  adjective  noun  verb(past-tense) ...
```

each word has a function within context of the sentence. you can combine different words to make different meanings.

why are we talking about this?

there are lots of types of codes, and in order to understand high level coding (or programming languages, as we sometimes call them)
it is helpful to understand the fundamentals of computation machines.

sometimes at work, when i talk about code, i'm talking about machine code. some smart people long ago figured out that you
can perform logical operations on a binary numerical system (i.e. radix-2, 10001010101...). some other smart people
figured out that you can build machines to operate on this binary system in order to run huge mathematical computations.
ones and zeros can be represented with electrical signals, a lightbulb that is on or off. the tiny silicon chips in your 
laptops can be used to maintain electrical state that represents numbers that represents high level concepts. its a bit reductive, but this 
is essentially the foundation of modern computing.


what's actually stored in a computer?
bits, electrical signals that represent the concept of 1 and 0, which we can use to do mathematical computations.

what does that mean?

every thing you see on your screen is just bits, that represent numbers. bits that represent color values
that make up the pixels on your monitor. number encodings for letters and characters that we read.
every program you execute on your computer is actually just bits.


if you want a gateway into coding, you'll need a programming language. i recommend [python](https://www.python.org/).
  - its well designed, readable, and concise
  - it has a strong developer community, with good libraries for data science and machine learning
  - there is a very strong learning-oriented community around python
    - its often used as a teaching language at top engineering schools like Harvey Mudd and MIT
    - lots of tutorials and resources
    - people are nice


what is a programming language?
-------------------------------

a programming language is an attempt by computer scientists to abstract away the complicated
nature of running computations with machine code. it is very difficult to program in bits.

the reason it is called a language is because they provide a syntax for human readable imperative
statements, which we can compile in to machine code (well, its more complicated
than this but let's just stick with that explanation).

when we write programs and code, we're just moving bits around.


let's break down parts of a programming language


each line in a program can be thought of as an imperative statement in a language,
`do X right now, wait for 5 minutes, then do Y`

you can compose lots of statements to do lots of complicated things. 
```python
do_laundry(clothes):
  wash(clothes, with soap)
  dry(clothes)
  fold(clothes)
```

when you combine several statements
into one ideological concept, we call this an `abstraction` and it allows us to further combine complex
ideas into one executable program.
```python
CleanHouse:
  do_laundry(clothes):
    wash(clothes, with soap)
    dry(clothes)
    fold(clothes)

  sweep(floors):
    ...

  clean(room):
    ...
```

there are two kinds of "clauses" in programming
- imperative
- conditional

```python
if (this condition is true):     # conditional
  do this thing                  # imperative
```

what kinds of things can you do?

you have data and you have operations

primitive types
- boolean
- integers (whole numbers)
- double/float (rational numbers, with finite precision)
- strings ("strings" of characters)
- arrays

primitive types are stored in `variables`, which are just user-defined word symbols
that represent data, stored in some location in memory
```python
x = 100
greeting = "Hello, friend"
```

you can also compose complex data types out of primitive types. we call these
`structs` or `classes`, or more generally, `types`.

```python
# warning: not literal python syntax!
# python doesn't have type declaration
class Office:
  integer headCount = 100
  string[] departments = [ "human resources", "partner services", "finances", "engineering" ]
```
  

operations
- math/logical operators
- conditional execution
  - if
  - while
  - for
- variable assignment
- functions


```python
# Fibonacci series up to n
>>> def fib(n):
>>>     a, b = 0, 1
>>>     while a < n:
>>>         print a,
>>>         a, b = b, a+b
>>>     print
>>> fib(1000)
0 1 1 2 3 5 8 13 21 34 55 89 144 233 377 610
```


what is the shell?
------------------

that is an existential question that i still haven't answered yet. some wise people tell me that it is a user interface
that provides access to an operating system's services. i think it is the gateway into the singularity.


```bash
cd
ls
vim
grep
awk/sed
python
```



how do you get started?
-----------------------

code a little every day

https://www.python.org/
https://projecteuler.net/
https://leetcode.com/

