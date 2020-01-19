---
title: "C Input/Output"
date: 2020-01-17T16:39:26-08:00
draft: false

description: Learn how to use the scanf() function to take input from the user and printf() function to display output to the user.
---

#### C Output
In C programming, printf() is one of the main output function. The function sends formatted output to the screen. For example,

<div class="py-2"></div>

---

<div class="py-2"></div>

##### Example 1: C Output

<div class="border p-3">
    #include <code>&lt;stdio&gt;</code>  
    <br/>
    int main() {
    <br/>
    // Displays the string inside quotations
    <br/>
    printf("C Programming");
    <br/>
    return 0;
    <br/>
    }
</div>
<div class="py-2"></div>

##### Output

<div class="py-2"></div>
<input value="C Programming" class="w-100 p-2">
<div class="py-2"></div>

How does this program work?

- All valid C programs must contain the main() function. The code execution begins from the start of the main() function.
- The printf() is a library function to send formatted output to the screen. The function prints the string inside quotations.
- To use printf() in our program, we need to include stdio.h header file using the #include <stdio.h> statement.
- The return 0; statement inside the main() function is the "Exit status" of the program. It's optional.

<div class="py-2"></div>

---

<div class="py-2"></div>

#### Example 2: Integer Output

<div class="border p-3">
    #include <code>&lt;stdio&gt;</code>  
    <br/>
    int main() {
    <br/>
    int testInteger = 5;
    <br/>
    printf("Number = %d", testInteger);
    <br/>
    return 0;
    <br/>
    }
</div>
<div class="py-2"></div>

##### Output

<div class="py-2"></div>
<input value="Number = 5" class="w-100 p-2">
<div class="py-2"></div>

To print float, we use %f format specifier. Similarly, we use %lf to print double values.

<div class="py-2"></div>

---

<div class="py-2"></div>

#### Example 2: Integer Output

<div class="border p-3">
    #include <code>&lt;stdio&gt;</code>  
    <br/>
    int main() {
    <br/>
    char chr = 'a';
    <br/>
    printf("character = %c.", chr);  
    <br/>
    return 0;
    <br/>
    }
</div>
<div class="py-2"></div>

##### Output

<div class="py-2"></div>
<input value="character = a
" class="w-100 p-2">
<div class="py-2"></div>

To print char, we use %c format specifier.

<div class="py-2"></div>

---

<div class="py-2"></div>

#### Example 2: Integer Output

<div class="border p-3">
    #include <code>&lt;stdio&gt;</code>  
    <br/>
    int main() {
    <br/>
    int testInteger;
    <br/>
    printf("Enter an integer: ");
    <br/>
    scanf("%d", &testInteger);  
    <br/>
    printf("Number = %d",testInteger); 
    <br/>
    return 0;
    <br/>
    }
</div>
<div class="py-2"></div>

##### Output

<div class="border p-3">
    Enter an integer: 4
    <br/>
    Number = 4
    <br/>
</div>
<div class="py-2"></div>

Here, we have used %d format specifier inside the scanf() function to take int input from the user. When the user enters an integer, it is stored in the testInteger variable.

Notice, that we have used &testInteger inside scanf(). It is because &testInteger gets the address of testInteger, and the value entered by the user is stored in that address.
