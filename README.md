# csci231-lab-4-solved
**TO GET THIS SOLUTION VISIT:** [CSCI231 Lab 4 Solved](https://www.ankitcodinghub.com/product/csci231-lab-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97022&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSCI231 Lab 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
1. Implement a procedure ​reverse in MIPS assembly language that, given a string ​S and its length​, reverses ​S​.

For example, if ​S =“Hello” and ​length = 5, then after calling your procedure ​S becomes “olleH”, and this reversed ​S should be printed out. (NOTE: ​S = “H ello” and length = 6, ​S becomes “olle H”, assuming each space will be calculated as an each length; also special characters will not be considered).

In the program, we assume the variables (e.g., ​S ​and​ length​) should be declared and initialized manually in the ​.data​ section. (Need to be tested by changing the​ S​ and ​length​ manually.)

The signature of this procedure in a high level language would look like this:

void reverse(char String[], int length); Output​: for ​S​ =“​Hello​”

With the printed ​olleH

The string ​S​ MUST have ​olleH ​(,with ASCII representation; the address might be different)

2. [​OP2​] Optionally, your program can use ​a prompt user​ to input a string ​S,​ and print reversed ​S out. And, the program should continue prompting until the user inputs “-”, i.e., until ​S​=“-”.

NOTE​: The option2 will not be supported by your TA, but optionally you can submit this version after working by yourself, who wants to try a more challenging problem. Please add the following message in ​the first line of your submitted program​: ​#[OP2] was implemented

For the optional problem, you need to refer more SYSCALL system services, in addition to the below examples: ​https://courses.missouristate.edu/KenVollmar/mars/Help/SyscallHelp.html

NOTES​: How to print Integers and Strings/space/newline using ‘syscall’ .data

</div>
</div>
<div class="layoutArea">
<div class="column">
x: msg1: nl: space:

main:

# Register assignments

</div>
</div>
<div class="layoutArea">
<div class="column">
.text

</div>
</div>
<div class="layoutArea">
<div class="column">
# $s0 = x

</div>
</div>
<div class="layoutArea">
<div class="column">
.word 5 .asciiz “x=” .asciiz “\n” .asciiz ” ”

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
# Initialize registers

</div>
</div>
<div class="layoutArea">
<div class="column">
lw

# Print li

la syscall

# Print li move syscall

# Print li

la syscall

# Exit li syscall

</div>
<div class="column">
$s0, x

msg1

$v0, 4 $a0, msg1

result (x) $v0,1 $a0, $s0

newline $v0,4 $a0, nl

$v0,10

</div>
<div class="column">
# Reg $s0 = x

# print_string syscall code = 4

# print_int syscall code = 1

# Load integer to print in $a0

# print_string syscall code = 4

# exit

</div>
</div>
</div>
</div>
