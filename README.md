# cis2500-assignment-2--recursion-solved
**TO GET THIS SOLUTION VISIT:** [CIS2500 Assignment 2- Recursion Solved](https://www.ankitcodinghub.com/product/cis2500-question-2-recursion-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115164&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CIS2500 Assignment 2- Recursion Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
2a. Recursive functions

• Implement the following functions using recursion (see the next page for examples) o Count up from 0 to n o Count down from 2n to 0 by 2 o nth, nth_sorted

§ this applies to Sorted Lists from Q1a o remove_nth, remove_nth_sorted

§ this applies to Sorted Lists from Q1a

2b. Greatest Common Divisor (GCD)

• Read up on the Euclidean Algorithm for solving GCD in Wikipedia o First Section: https://en.wikipedia.org/wiki/Euclidean_algorithm o Procedure: https://en.wikipedia.org/wiki/Euclidean_algorithm#Procedure o Example: https://en.wikipedia.org/wiki/Euclidean_algorithm#Worked_example o Using mod: https://en.wikipedia.org/wiki/Euclidean_algorithm#Euclidean_division o Implementations: https://en.wikipedia.org/wiki/Euclidean_algorithm#Implementations

• Examine the final implementation, which is recursive, and implement it in C o it should have the signature long gcd(long, long)

• This implementation (as yours should be) is naturally “tail recursive” o explain why it is tail recursive in the readme

o make sure your make file uses the appropriate gcc flag to run tail recursive code efficiently

To test question 2

Write a program called a4q2.c

• The program must read in a text file that contains a series of commands, one per line, with the name of the text file entered as a command line argument o Base this code on the code you used in q1a to implement command entries from a file o However, the code will need to be extended to allow for new commands that are detailed below

• Some of the questions in 2a use the Sorted_List data type with key_type as double and value_type as int, the same as a4q1a_int.c.

o So when compiling files containing Sorted_List functions in your make file, use –DINT

• All new commands for entry from the input file are listed on the next page

The assignment concludes with Question 3: Fraction ADT to be released early next week

List of Commands from the Input File

All commands from q1a should be made available as well as the following

• count_up n

o Prints the integers from 0 to n on a single line, comma separated, with 5 spaces before o Using the following commands count_up 4 the output should be

count_up from 0 to 4

0, 1, 2, 3, 4

• count_down n

o Same as count_up, but printing the integers down from 2n to 0 on by 2 o Using the following commands count_down 4 the output should be

count_down from 8 to 0 by 2

8, 6, 4, 2, 0

• nth n order o Displays the nth element in the list according to the order specified (inserted or key sort) on its own line as key value

§ Indented 5 spaces with 2 spaces between the key and the value

§ Firsts prints the command – see below for an example o Using the input from the append examples in q1a and the following commands print_all nth 1 INSERTED_ORDER nth 1 SORTED_ORDER the output should be

print_all: Insertion Order

3.27 1427

0.94 984

7.21 346

nth: n = 1, Insertion Order

0.94 984

nth: n = 1, Key Sort Order 3.27 1427

• remove_nth n order o removes the nth element in the list according to the order specified (inserted or key sort) and displays the removed element on its own line as key value

o Again using the input from the append examples in q1a For the commands

remove_nth 2 INSERTED_ORDER print_all

remove_nth 1 SORTED_ORDER print_all

the output should be

remove_nth: n = 2, Insertion Order

7.21 346

print_all: Insertion Order

3.27 1427

0.94 984

remove_nth: n = 1, Key Sort Order

3.27 1427

print_all: Insertion Order 0.94 984
