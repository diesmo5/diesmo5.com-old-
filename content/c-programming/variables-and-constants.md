---
title: "C Variables, Constants, and Literals"
date: 2020-01-17T16:37:33-08:00
draft: false

description: Learn about variables, rules for naming variables, different literals and how to create constants in the C programming language.
---

#### Variables

###### In programming, a variable is a container (storage area) to hold data.

###### To indicate the storage area, each variable should be given a unique name (identifier). Variable names are just the symbolic representation of a memory location. For example:

<div class="py-2"></div>
<input value="int playerScore = 95;" class="w-100 p-2"/>
<div class="py-4"></div>

###### Here, playerScore is a variable of int type. Here, the variable is assigned an integer value 95
<div class="py-2"></div>

###### The value of a variable can be changed, hence the name variable.

<div class="border p-3">
    char ch = 'a';
    <br/>
    // some code
    <br/>
    ch = 'l';
</div>

<div class="py-2"></div>

#### Rules for naming a variable
1. A variable name can have only letters (both uppercase and lowercase letters), digits and underscore.
2. The first letter of a variable should be either a letter or an underscore.
3. There is no rule on how long a variable name (identifier) can be. However, you may run into problems in some compilers if the variable name is longer than 31 characters.

###### Note: You should always try to give meaningful names to variables. For example: firstName is a better variable name than fn.
<div class="py-2"></div>

###### C is a strongly typed language. This means that the variable type cannot be changed once it is declared. For example:

<div class="border p-3">
    int number = 5;      // integer variable    
    <br/>
    number = 5.5;        // error
    <br/>
    double number;       // error
</div>
<div class="py-2"></div>

###### Here, the type of number variable is int. You cannot assign a floating-point (decimal) value 5.5 to this variable. Also, you cannot redefine the data type of the variable to double. By the way, to store the decimal values in C, you need to declare its type to either double or float.
<div class="py-2"></div>

---
<div class="py-2"></div>

#### Literals
###### Literals are data used for representing fixed values. They can be used directly in the code. For example: 1, 2.5, 'c' etc.
<div class="py-2"></div>

###### Here, 1, 2.5 and 'c' are literals. Why? You cannot assign different values to these terms
<div class="py-2"></div>

---
<div class="py-2"></div>

#### 01 Integers
###### An integer is a numeric literal(associated with numbers) without any fractional or exponential part. There are three types of integer literals in C programming:

- decimal (base 10)
- octal (base 8)
- hexadecimal (base 16)

<div class="py-2"></div>

###### For example:

<div class="border p-3">
    Decimal: 0, -9, 22 etc
    <br/>
    Octal: 021, 077, 033 etc
    <br/>
    Hexadecimal: 0x7f, 0x2a, 0x521 etc
</div>
<div class="py-2"></div>

###### In C programming, octal starts with a 0, and hexadecimal starts with a 0x.
<div class="py-2"></div>

---
<div class="py-2"></div>

#### 02 Floating-point Literals
###### A floating-point literal is a numeric literal that has either a fractional form or an exponent form. For example:

<div class="border p-3">
    -2.0
    <br/>
    0.0000234
    <br/>
    -0.22E-5
</div>
<div class="py-2"></div>


---
<div class="py-2"></div>

#### 03 Characters
###### A character literal is created by enclosing a single character inside single quotation marks. For example: 'a', 'm', 'F', '2', '}' etc.
<div class="py-2"></div>


---
<div class="py-2"></div>

#### 04 Escape Sequences
###### Sometimes, it is necessary to use characters that cannot be typed or has special meaning in C programming. For example: newline(enter), tab, question mark etc.
<div class="py-2"></div>

###### In order to use these characters, escape sequences are used.
<div class="py-2"></div>

<div class="row">
    <div class="col-6">
        <input value="Escape Sequences" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="Character" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="\b" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="Backspace" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="\f" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="Form feed" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="\n" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="Newline" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="\r" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="Return" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="\t" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="Horizontal tab" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="\v" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="Vertical tab" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="\\" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="Backslash" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="\'" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="Single quotation mark" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="\``" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="Double quotation mark" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="\?" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="Question mark" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="\0" class="w-100 p-2">
    </div>
    <div class="col-6">
        <input value="Null character" class="w-100 p-2">
    </div>
</div>
<div class="py-2"></div>


---
<div class="py-2"></div>

###### For example: \n is used for a newline. The backslash \ causes escape from the normal way the characters are handled by the compiler.
<div class="py-2"></div>


---
<div class="py-2"></div>

#### 05 String Literals
###### A string literal is a sequence of characters enclosed in double-quote marks. For example:
<div class="py-2"></div>

<div class="border p-3">
    "good"                  //string constant
    <br/>
    ""                     //null string constant
    <br/>
    "      "               //string constant of six white space
    <br/>
    "x"                    //string constant having a single character.
    <br/>
    "Earth is round\n"         //prints string with a newline
</div>
<div class="py-2"></div>

---
<div class="py-2"></div>

#### Constants
###### If you want to define a variable whose value cannot be changed, you can use the const keyword. This will create a constant. For example,

<div class="py-2"></div>
<input value="const double PI = 3.14;" class="w-100 p-2">
<div class="py-2"></div>

###### Notice, we have added keyword const.
<div class="py-2"></div>

###### Here, PI is a symbolic constant; its value cannot be changed.

<div class="border p-3">
    const double PI = 3.14;
    <br/>
    PI = 2.9; //Error
</div>
<div class="py-2"></div>

---

<div class="py-2"></div>

###### You can also define a constant using the #define preprocessor directive. We will learn about it in C Macros tutorial.

