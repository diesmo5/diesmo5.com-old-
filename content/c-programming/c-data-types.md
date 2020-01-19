---
title: "C Data Types"
date: 2020-01-17T16:37:49-08:00
draft: false

description: Learn about basic data types such as int, float, char etc. in C programming.
---


##### In C programming, data types are declarations for variables. This determines the type and size of data associated with variables. For example,

<div class="py-2"></div>
<input value="int myVar;" class="w-100 p-2">
<div class="py-2"></div>

###### Here, myVar is a variable of int (integer) type. The size of int is 4 bytes.
<div class="py-2"></div>

#### Basic types
###### Here's a table containing commonly used types in C programming for quick access.

<div class="row">
    <div class="col-4">
        <input value="Type" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="Size (bytes)" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="Format Specifier" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="int" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="at least 2, usually 4" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="%d" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="char" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="1" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="%c" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="float" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="4" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="%f" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="double" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="8" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="%lf" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="short int" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="2 usually" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="%hd" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="unsigned int" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="at least 2, usually 4" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="%u" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="long int" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="at least 4, usually 8" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="%li" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="long long int" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="at least 8" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="%lli" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="unsigned long int" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="at least 4" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="%lu" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="unsigned long long int" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="at least 8" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="%llu" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="signed char" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="1" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="%c" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="unsigned char" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="1" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="%c" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="long double" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="at least 10, usually 12 or 16" class="w-100 p-2">
    </div>
    <div class="col-4">
        <input value="%lf" class="w-100 p-2">
    </div>
</div>
<div class="py-4"></div>

#### int
###### Integers are whole numbers that can have both zero, positive and negative values but no decimal values. For example, 0, -5, 10
<div class="py-2"></div>

###### We can use int for declaring an integer variable.

<div class="py-2"></div>
<input value="int id;" class="w-100 p-2">
<div class="py-2"></div>

###### Here, id is a variable of type integer.
<div class="py-2"></div>

###### You can declare multiple variables at once in C programming. For example,

<div class="py-2"></div>
<input value="int id, age;" class="w-100 p-2">
<div class="py-2"></div>

###### The size of int is usually 4 bytes (32 bits). And, it can take 232 distinct states from -2147483648 to 2147483647.

<div class="py-2"></div>

---

<div class="py-2"></div>

#### float and double

float and double are used to hold real numbers.

<div class="border p-3">
    float salary;
    <br/>
    double price;
</div>
<div class="py-2"></div>

In C, floating-point numbers can also be represented in exponential. For example,

<div class="py-2"></div>
<input value="float normalizationFactor = 22.442e2;" class="w-100 p-2">
<div class="py-2"></div>

What's the difference between float and double?

<div class="py-2"></div>

The size of float (single precision float data type) is 4 bytes. And the size of double (double precision float data type) is 8 bytes.

<div class="py-2"></div>

---

<div class="py-2"></div>

#### char
Keyword char is used for declaring character type variables. For example,

<div class="py-2"></div>
<input value="char test = 'h';" class="w-100 p-2">
<div class="py-2"></div>

The size of the character variable is 1 byte.

<div class="py-2"></div>

---

<div class="py-2"></div>

#### void
void is an incomplete type. It means "nothing" or "no type". You can think of void as absent.

<div class="py-1"></div>

For example, if a function is not returning anything, its return type should be void.

<div class="py-1"></div>

Note that, you cannot create variables of void type.

<div class="py-2"></div>

---

<div class="py-2"></div>

#### short and long
If you need to use a large number, you can use a type specifier long. Here's how:

<div class="border p-3">
    long a;
    <br/>
    long long b;
    <br/>
    long double c;
</div>
<div class="py-2"></div>

Here variables a and b can store integer values. And, c can store a floating-point number.

If you are sure, only a small integer ([−32,767, +32,767] range) will be used, you can use short.

<div class="py-2"></div>
<input value="short d;" class="w-100 p-2">
<div class="py-2"></div>

You can always check the size of a variable using the sizeof() operator.

<div class="border p-3">
    #include <code>&lt;stdio&gt;</code>  
    <br/>
    int main() {
    <br/>
        short a;
    <br/>
        long b;
    <br/>
        long long c;
    <br/>
        long double d;
    <br/>
        printf("size of short = %d bytes\n", sizeof(a));
    <br/>
        printf("size of long = %d bytes\n", sizeof(b));
    <br/>
        printf("size of long long = %d bytes\n", sizeof(c));
    <br/>
        printf("size of long double= %d bytes\n", sizeof(d));
    <br/>
        return 0;
    <br/>
    }
</div>

<div class="py-2"></div>


<div class="py-2"></div>

---

<div class="py-2"></div>

#### signed and unsigned
In C, signed and unsigned are type modifiers. You can alter the data storage of a data type by using them. For example,

<div class="border p-3">
    unsigned int x;
    <br/>
    int y;
</div>
<div class="py-2"></div>

Here, the variable x can hold only zero and positive values because we have used the unsigned modifier.

<div class="py-2"></div>

---

<div class="py-2"></div>

Other data types defined in C programming are:

- bool Type
- Enumerated type
- Complex types

<div class="py-2"></div>

---

<div class="py-2"></div>

#### Derived Data Types
Data types that are derived from fundamental data types are derived types. For example: arrays, pointers, function types, structures, etc.

We will learn about these derived data types in later tutorials.



