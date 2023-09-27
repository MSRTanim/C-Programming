# C-Programming
This is a source file for C Programming Language. Read attentively the Redme file...

[![MasterHead](https://media.tenor.com/qJ5evVs-_uUAAAAC/coding.gif)](http://www.msrtanim.xyz)

# C Language CheatSheet
This C cheatsheet is aimed to provide you with a quick syntax revision of C language. This will be helpful for students who need a quick syntax revision right before their exams or professionals to quickly look at the C language syntax. Let's start with the basics and move toward the more intricate aspects of C programming.
## Basics
Basic syntax and functions from the C programming language.

## Boilerplate Code

      #include <stdio.h> //hader files
      int main () //main function
      {
            //Your code here
            return (0); //returning value to int main()
      }


## printf function
It is used to show output on the screen

      printf("Hello World!")

## Scanf function
It is used to take input from the user

      scanf("format_specifier", &variables)
      int a;

We use & with the variable name to represent "address of". This is how the syntax works:

      scanf("%d",&a); // Store keyboard input in a variable with address (address of a or &a)
      printf("%d",&a);

## Comments
A comment is a code that is not executed by the compiler, and the programmer uses it to annotate their code, providing explanations or reminders about the code's functionality, which aids in readability and future maintenance.

## Single line comment

      // This is a single line comment

## Multi-line comment

      /* This is a 
      multi-line
      comment
      */

## Data types
The data type defines the kind of data that can be stored in a variable, such as integers, floating-point numbers, characters, or more complex structures. It dictates how the data is stored, interpreted, and manipulated within the program.

## Character type
The character type, often represented as a single octet (one byte), is used to store individual characters in the C programming language.

      char variable_name;

The format specifier for a character in C is "%c". To print a character, we use this specifier within the printf function, following the syntax like this:
      
      char x;
      scanf(" %c",&x);
      printf("character is %c",x)

## Integer type
To store non-decimal numeric values, an integer type is used

      int variable_name;

The format specifier of an integer is "%d"

      int a;
      scanf("%d",&a);
      printf("%d",a);

## Float type
To store decimal numeric values, float type is used

      float variable_name;

The format specifier of a float is "%f"

      float b;
      scanf("%f",&b);
      printf("%f",b);

## Double type
To store a double-precision floating-point value we use double.

      double variable_name;

The format specifier of double is "%f"

      double ch;
      scanf("%lf",&ch);
      printf("%lf",ch);

## Void type
The void type in C represents the absence of a type. It's often used in function declarations to specify that the function does not return any value. For example:

      void myFunction() {
      // Function code here
      }
In this context, the void keyword indicates that myFunction does not return a value. It can also be used for function parameters to indicate that a function takes no arguments

## Escape Sequences
Escape sequences in C are combinations of characters that begin with a backslash (\) and are used to represent characters that cannot be typed directly. These sequences are interpreted in a special way when used inside string literals or character constants.

For example, the escape sequence \n represents a newline character, and \t represents a tab character. Here are some escape sequence characters used in C language.

## Alarm or Beep
\a produces a beep sound

      #include<stdio.h>
      int main()
      {
      printf("\a"); // It produces a beep sound
      return 0;
      }

## Backspace
\b adds a backspace

      #include<stdio.h>
      int main()
      {
    printf("Hello\bWorld"); // It prints "HellWorld"
    return 0;
    }

## Form feed

      #include<stdio.h>
      int main()
      {
    printf("Page break here\fContinue text"); // It may create a page break, but it's not supported everywhere
    return 0;
    }

## Newline
Newline Character

      #include<stdio.h>
      int main()
      {
    printf("Line one\nLine two"); // Prints two lines
    return 0;
    }

## Carriage return
The carriage return, represented by the escape sequence \r in the C programming language, is a control character that resets the cursor position to the beginning of the current line. It doesn't erase any characters but simply moves the cursor to the start of the line. The string "Hello" is printed first, then the carriage return moves the cursor back to the beginning of the line, and "World" is printed, overwriting "Hello."

      #include<stdio.h>
      int main()
      { 
    printf("Hello\rWorld"); // Outputs "World" but behavior might vary depending on the OS
    return 0;
    }

## Tab
It gives a tab space

      #include<stdio.h>
      int main()
      {
    printf("Tabbed\ttext"); // Adds a tab space
    return 0;
    }

## Backslash
It adds a backslash

      #include<stdio.h>
      int main()
      {
    printf("\\"); // Prints a backslash
    return 0;
    }

## Single quote
It adds a single quotation mark

      #include<stdio.h>
      int main()
      {
    printf("\'"); // Prints a single quotation mark
    return 0;
    }
    
## Question mark
It adds a question mark

      #include<stdio.h>
      int main()
      {
    printf("\?"); // Prints a question mark
    return 0;
    }

## Octal No.
It represents the value of an octal number

      #include<stdio.h>
      int main()
      {
    printf("\101"); // Prints 'A', which is 101 in octal
    return 0;
    }
    
## Hexadecimal No.
It represents the value of a hexadecimal number

      #include<stdio.h>
      int main()
      {
    printf("\x41"); // Prints 'A', which is 41 in hexadecimal
    return 0;
    }

## Null
The null character is usually used to terminate a string

      #include<stdio.h>
      int main()
      {
    printf("\0");
    char str[] = "Hello\0World"; // The null character is used to terminate a string
    return 0;
    }
    
## Conditional Instructions
Conditional statements are used to perform operations based on some condition.
## If Statement

      if (/* condition */)
      {
    /* code */
    }

## If-else Statement

      if (/* condition */)
      {
    /* code */
    }
    else{
    /* Code */
    }


## if else-if Statement

      if (condition) {
    // Statements;
    }
    else if (condition){
    // Statements;
    }
    else{
    // Statements
    }

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git

## Boilerplate Code

      pkg intall git
      


[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00F716&width=435&lines=%F0%9F%91%8BHELLO+WORLD+I'M+TANIM+HERE%F0%9F%92%81%F0%9F%8F%BB%E2%80%8D%E2%99%82%EF%B8%8F;%E2%98%A3%EF%B8%8FCEO+OF+TOXIC+CYBER+SECURITY%E2%98%A3%EF%B8%8F;%F0%9F%92%81%F0%9F%8F%BB%E2%80%8D%E2%99%82%EF%B8%8FPLEASE+FOLLOW+MY+GITHUB%F0%9F%92%96;%F0%9F%92%BBTHANKS+ALL+MY+FAMILY+MEMBERS%F0%9F%94%A5)](https://git.io/typing-svg)

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=24F709&width=435&lines=%E2%9A%A0%EF%B8%8FONLY+TERMUX+TERMINAL+CAN+RUN+THIS%E2%9A%A0%EF%B8%8F)](https://git.io/typing-svg)


[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=00F716&width=435&lines=YOU+RESPECT+ME%2C+I+RESPECT+YOU%F0%9F%A5%B0;YOU+DESPECT+ME%2C+I+FUCK+YOU%F0%9F%96%95%F0%9F%8F%BB)](https://git.io/typing-svg)

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://fb.com/msrtanim1" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="msrtanim1" height="30" width="40" /></a>
<a href="https://instagram.com/msrtanim1" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="msrtanim1" height="30" width="40" /></a>
<a href="https://www.youtube.com/c/msrtanim" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/youtube.svg" alt="msrtanim" height="30" width="40" /></a>
<a href="https://twitter.com/msrtanim_" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/twitter.svg" alt="msrtanim_" height="30" width="40" /></a>
<a href="https://codepen.io/msrtanim" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/codepen.svg" alt="msrtanim" height="30" width="40" /></a>
<a href="https://discord.gg/4Y4KUUADMC" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="4292" height="30" width="40" /></a>
</p>
