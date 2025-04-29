# cse320---solved
**TO GET THIS SOLUTION VISIT:** [CSE320 – Solved](https://www.ankitcodinghub.com/product/cse320-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;110577&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE320 -  Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Assignment Overview

This assignment develops familiarity with arrays in assembly language. You will develop a set of ARM assembly language functions which implement common string operations.

Assignment Deliverables

The deliverables for this assignment are the following files:

proj10.support.s – the source code for your support module proj10.driver.c – the source code for your driver module proj10.makefile – the makefile which produces proj10

Be sure to use the specified file names and to submit them for grading via the CSE handin system.

Assignment Specifications

A low-level character string is defined as a sequence of zero or more characters in an array of type “char”, with a null byte to mark the end of the string.

1. You will develop the ARM assembly language functions listed below:

unsigned int length( const char* source );

void copy( char* dest, const char* source );

void append( char* dest, const char* source );

char* duplicate( const char* source );

int compare( const char* source1, const char* source2 );

Those five functions (and any “helper” functions which you develop) will constitute a module named

“proj10.support.s”. The functions in that module will not call any C library functions except function “malloc”.

Function “length” will return the number of characters in string “source”; the count will not include the terminating null byte.

Function “copy” will copy the contents of string “source” into string “dest”.

Function “append” will append the contents of string “source” to the end of string “dest”.

Function “duplicate” will return the address of a duplicate of string “source”; it will use function “malloc” to allocation additional memory and will copy string “source” into that memory.

Function “compare” will return the results of comparing string “source1” and string “source2”. If “source1” and “source2” are equal, it will return 0. If “source1” is less than “source2”, it will return a negative integer. If “source1” is greater than “source2”, it will return a positive integer.

2. You will develop a driver module to test your implementation of the support module. The driver module will consist of function “main” and any additional helper functions which you choose to implement. All output will be appropriately labeled.

Assignment Notes

2. Your program will be translated and linked using “gcc”. For example, the following commands could be used to translate and link your program, then load and execute it:

&lt;prompt&gt; gcc -c proj10.support.s

&lt;prompt&gt; gcc –Wall –c proj10.driver.c

&lt;prompt&gt; gcc proj10.support.o proj10.driver.o –o proj10 &lt;prompt&gt; proj10

3. In order to interface ARM assembly language functions with C functions, you must follow certain conventions about register usage.

The calling function will place up to four parameters in registers R0 through R3 (with the first argument in register R0).

The called function must save and restore registers R4 through R11 if it uses any of those registers (the calling function assumes that registers R4 through R11 are not altered by calling another function).

The called function place its return value in register R0 before returning to the calling function.

Registers R12, R13, R14 and R15 are used by the system and their contents must not be modified by your functions.
