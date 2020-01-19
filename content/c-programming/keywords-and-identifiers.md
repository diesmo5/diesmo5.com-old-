---
title: "Keywords and Identifiers"
date: 2020-01-17T13:47:48-08:00
draft: false

description: Learn about keywords. keywords are reserved words in C Programming that are part of the syntax. Also, you will learn about identifiers and how to name them.

sectionOneTitle: Character Set
sectionOneText: A character set is a set of alphabets, letters and some special characters that are valid in C language.
---

#### Character set

###### A character set is a set of alphabets, letters, and some special characters that are valid in the C language.

<div class="py-3"></div>

#### Alphabets
###### C accepts both lowercase and uppercase alphabets as variables and functions.
<div class="py-2"></div>

###### Uppercase: A B C ............................ X Y Z
###### Lowercase: a b c ............................ x y z

<div class="py-3"></div>

#### Digits
###### 0 1 2 3 4 5 6 7 8 9

<div class="py-3"></div>

#### Special Characters
###### Special Characters in C Programming

,	<	>	.	_
(	)	;	$	:
%	[	]	#	?
'	&	{	}	"
^	!	*	/	|
-	\	~	+	 

<div class="py-3"></div>

###### White space Characters
Blank space, newline, horizontal tab, carriage, return and form feed.

<div class="py-3"></div>

#### C Keywords
###### Keywords are predefined, reserved words used in programming that have special meanings to the compiler. Keywords are part of the syntax and they cannot be used as an identifier. For example:

<input value="int money;" class="w-100 p-2">


<div class="py-3"></div>

###### int is a keyword that indicates money is a variable of type int (integer).
<br>

###### As C is a case sensitive language, all keywords must be written in lowercase. Here is a list of all keywords allowed in ANSI C.
<br>

#### Keywords List
<div class="row">
    <div class="col-lg-3 col-md-4 col-6">
        <input value="auto" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="double" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="int" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="struct" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="break" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="else" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="long" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="switch" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="case" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="enum" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="register" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="typedef" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="char" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="extern" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="return" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="union" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="continue" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="for" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="signed" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="void" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="do" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="if" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="static" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="while" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="default" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="goto" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="sizeof" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="volatile" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="const" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="float" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="short" class="w-100 p-2">
    </div>
    <div class="col-lg-3 col-md-4 col-6">
        <input value="unsigned" class="w-100 p-2">
    </div>
</div>
<br/>

#### C Identifiers
###### Identifier refers to name given to entities such as variables, functions, structures etc.

###### Identifiers must be unique. They are created to give a unique name to an entity to identify it during the execution of the program. For example:
<br/>

<input value="int money;" class="w-100 p-2">
<input value="double accountBalance;" class="w-100 p-2">
<br/>

###### Here, money and accountBalance are identifiers.

###### Also remember, identifier names must be different from keywords. You cannot use int as an identifier because int is a keyword.
<br/>

#### Rules for naming identifiers
1. A valid identifier can have letters (both uppercase and lowercase letters), digits and underscores.
2. The first letter of an identifier should be either a letter or an underscore.
3. You cannot use keywords as identifiers.
4. There is no rule on how long an identifier can be. However, you may run into problems in some compilers if the identifier is longer than 31 characters.

###### You can choose any name as an identifier if you follow the above rule, however, give meaningful names to identifiers that make sense. 














