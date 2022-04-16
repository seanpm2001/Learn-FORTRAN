
***

![/Fortran_logo.svg](/Fortran_logo.svg)

### Learning Fortran

I am not too experienced with Fortran at the moment. This document will go over my knowledge of the Fortran language so far.

This document used various versions of the Fortran programming language. The version will be listed with each example.

#### Comments in Fortran

Comments in Fortran are unique, but still easy to do.

```Fortran
C This is a single line comment
C Fortran does not support multi-line comments (as far as I know)
```

Fortran does not support comments after the first character in a line. Comments and source code can't be on the same line.

This example works with every version of Fortran.

#### Break keyword in Fortran

Fortran does NOT support the `break` keyword.

To this day, I am still not entirely sure what the `break` keyword does, but most languages support it.

_/!\ This example has not been tested yet, and may not work_

#### Hello World in Fortran

A hello world program in Fortran is a bit more complicated than a Python or Perl Hello World program, but it isn't very difficult either. It is not similar to any language I am currently familiar with.

```Fortran
program helloworld
print *,'Hello World'
end program helloworld
```

This example is for Fortran 95 and up.

_/!\ This example has not been tested yet, and may not work_

#### Functions in Fortran

Functions work like so in Fortran

```fortran
FUNCTION myFunc(argument list)
	print *, "Argument 1"
	print *, "Argument 2"
END FUNCTION myFunc
return myFunc
STOP
```

This example is for Fortran 95 and up.

_/!\ This example has not been tested yet, and may not work_

#### STOP keyword in Fortran

The `STOP` keyword goes at the end of a Fortran program to tell it to stop.

```fortran
program genericProgram
     print *, "Sample text"
end program genericProgram
STOP
```

This example is for Fortran 95 and up

_/!\ This example has not been tested yet, and may not work_

#### Booleans in Fortran

Booleans are defined like so in Fortran:

**I don't know how to implement Booleans in Fortran yet.**

_/!\ This example has not been tested yet, and may not work_

#### Int keyword in Fortran

Fortran supports the `int` keyword, but I don't know what it does.

```fortran
int x = 1
```

This example is for Fortran 95 and up

_/!\ This example has not been tested yet, and may not work_

#### Integer keyword in Fortran

Fortran supports the `integer` keyword, but I don't know what it does. I don't know what separates it from the `int` keyword.

```fortran
integer y = 2
```

This example is for Fortran 95 and up

_/!\ This example has not been tested yet, and may not work_

#### Goto keyword in Fortran

Fortran supports the `goto` keyword. Back in the days of punch cards, people would write programs with a zero instead an o. These used to be valid, but were removed before Fortran 95

```fortran
G0T0 10
```

This example is for FORTRAN I, II, III, and IV

_/!\ This example has not been tested yet, and may not work_

```fortran
goto 10
```

This example is for Fortran 95 and up

_/!\ This example has not been tested yet, and may not work_

#### Source

The majority of my Fortran knowledge comes from self-experimentation, and Wikipedia.

#### Other knowledge of Fortran

1. Fortran is not curly bracket and semicolon language

2. Fortran used to be spelled as FORTRAN, but was changed to lower case in the 1960s/1970a

3. Fortran is the 2nd oldest programming language that is still in development and is still in active use.

4. Fortran uses various file extensions, including `*.F` `*f` `*.FOR` `*.for` `*.f77` `*.f90` `*.f95` `*.f02` `*.f07` and more.

5. Fortran is a language recognized by GitHub

6. I don't know if Fortran is an open source language or not

7. Fortran was created by IBM

8. Fortran started out as a punchcard language, as disk storage didn't exist yet

9. No other knowledge of Fortran at the moment.

***

**File version:** `1 (2022, Thursday, April 14th at 11:16 pm PST)` - Prepared a day early

***
