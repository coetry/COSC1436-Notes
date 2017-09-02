# Intro 

We all take for granted conveniences that are made 
possible through the power of software. The internet
has changed the world, and now cryptocurrencies are
doing the same. All made possible through the power 
of software.

> "Software is eating the world"
> - Marc Andreessen

## A Brief Overview of the History of Computers

The first device known to carry out calculations was the [abacus](https://en.wikipedia.org/wiki/Abacus). It could only do addition and subtraction.

In 1642, [Blaise Pascal](https://en.wikipedia.org/wiki/Blaise_Pascal) invented another calculating device called the [Pascaline](https://en.wikipedia.org/wiki/Pascal%27s_calculator). This was also limited to just addition and subtraction

Later in the 17th Centure, [Gottfried von Leibniz](https://en.wikipedia.org/wiki/Gottfried_Wilhelm_Leibniz) invented a device that was able to add, subtract, multiply and divide.

- - -
_it's interesting how we take simple arithmetic and calculations for granted_
- - -

In 1819, [Joseph Jacquard](https://en.wikipedia.org/wiki/Joseph_Marie_Jacquard) discovered that instructions for weaving his looms could be stored on hole-punched cards. A weaver was able to rearrange cards to modify the patterns being woven. These cards were programming looms to make patterned clothing. Cool stuff. The idea of storing information in cards that served as instructions for a machine process, set the foundation for modern programming and computers.

In the mid-1800s [Charles Babbage](https://en.wikipedia.org/wiki/Charles_Babbage) designed two calculating machines: the [difference engine](https://en.wikipedia.org/wiki/Difference_engine) and the [analytical engine](https://en.wikipedia.org/wiki/Analytical_Engine). 

> The Analytical Engine incorporated an arithmetic logic unit, control flow in the form of conditional branching and loops, and integrated memory, making it the first design for a general-purpose computer that could be described in modern terms as Turing-complete. - Wikipedia

At the end of the 19th century, U.S. Census officials needed something to help them keep track of and organize the cencus data. [Herman Hollerith](https://en.wikipedia.org/wiki/Herman_Hollerith) created a calculating machine that ran on electricity and used punched cards to store data. He later founded the Tabulating Machine Company that later became __IBM__.

The [Mark I](https://en.wikipedia.org/wiki/Harvard_Mark_I) was built together by IBM and Harvard under the leadership of [Howard Aiken](https://en.wikipedia.org/wiki/Howard_H._Aiken). Punch cards were used to feed data. 

The computers that we use today use design rules given by [John von Neumann](https://en.wikipedia.org/wiki/John_von_Neumann):
	* Arithmetic Logic
	* A control unit
	* Memory
	* Input/Output devices

Von Neumann's design allows the programming instructions and data to share the same memory space.

In 1956 [transistors](https://en.wikipedia.org/wiki/Transistor) were invented which opened the door for faster, smaller, and more energy-efficient computers. [FORTRAN](https://en.wikipedia.org/wiki/Fortran) and [COBOL](https://en.wikipedia.org/wiki/COBOL). Integrated circuit chips came next and were faster, cheaper, and smaller. Thousands of circuits were abled to fit on a single a chip.

In 1970, the microprocessor was invented (an entire CPU on a single chip). 

[Wozniak](https://en.wikipedia.org/wiki/Steve_Wozniak) and [Jobs](https://en.wikipedia.org/wiki/Steve_Jobs) built the [Apple I](https://en.wikipedia.org/wiki/Apple_I) in their garage in 1977.

In 1981, IBM launches their own PC. 

We now have computers in our pocket capable of doing advanced AI operations (Siri - NLP) and so much more. All thanks to the hard work of the pioneers that paved the way.

## The Evolution of Programming Languages

Machine Language is the most basic computer language and provides program instructions in bits. Although most computers perform the same types of opertions, the computer designers may choose different sets of _binary codes_ to perform these operations

Different machines and architectures have different machine languages specific to them. To calculate something like: `wages = rate * hours` in a machine language, you would have something like ...

```
100100 010001
100110 010010
100010 010011
```

... where `100100` represents _load_, `100110` represents _multiplication_, and `100010` represents _store_.


Assembly languages were later created and used __mnemonics__ to help programmersremember instructions.


| Assembly Language  | Machine Language |
|--------------------|------------------|
| LOAD               | 100100           | 
| STOR               | 100010           | 
| MULT               | 100110           | 
| ADD                | 100101           | 
| SUB                | 100011           | 

Since a computer can't directly execute assembly language instructions, they need to be translated to machine code through an [assembler](https://en.wikipedia.org/wiki/Assembly_language#Assembler).

Even though Assembly is easier to write than raw machine code, it still requires the programmer to think in terms of individual processing instructions and is very taxing to solve simple problems. This is why _higher-level_ languages such as FORTRAN, COBOL, C, C++, and Java were created. Nowadays, even those languages are considered to be low-level languages and scripting languages like Perl, Ruby, and Python and thought of as higher-level. Just like Assembly code is translated to machine code through an assembler, code from languages like C++ are translated to machine code through a compiler. 



















