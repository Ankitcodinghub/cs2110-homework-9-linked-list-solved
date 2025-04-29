# cs2110-homework-9-linked-list-solved
**TO GET THIS SOLUTION VISIT:** [CS2110 Homework 9-Linked List Solved](https://www.ankitcodinghub.com/product/cs-2110-homework-9-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109437&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2110 Homework 9-Linked List Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
&nbsp;

1 Overview

1.1 Purpose

The purpose of this assignment is to introduce you to dynamic memory allocation in C. You will also learn how to implement a singly-linked list data structure in C.

How do we allocate memory on the heap? How do we de-allocate it when it is no longer used?

The goal of this assignment is to learn how to dynamically allocate and de-allocate memory, or manage memory, in C.

1.2 Task

In this assignment, you will be implementing a singly-linked list data structure. Your linked list nodes will have String-data (of type char *). Your linked list will be able to add, remove, and mutate, and query the data stored within it.

You will be writing code in

1. list.c

2. main.c

(main.c is only for your own testing purposes)

1.3 Criteria

You will be graded on your ability to implement the linked list data structure properly. Your implementation must be as described by each function’s documentation. Your code must manage memory correctly, meaning it must be free of memory leaks.

Note: A memory leak is when a block of memory is allocated for some purpose, and never de-allocated before the program loses all references to that block of memory.

2 Instructions

2.1 Implementation

You have been given one C file – list.c in which to implement the data structure. Implement all functions in this file. Each function has a block comment that describes exactly what it should do.

Be sure not to modify any other files. Doing so will result in point deductions that the tester will not reflect.

Remember that the string data passed to certain methods (char *data) is malloc-ed data. However, this data is malloc-ed separately from the node structs that contain it.

Forgetting to free this data when it is removed can cause memory leaks, but freeing it when it should be returned to the user can cause a use-after-free scenario. Keep this in mind when writing your list methods.

You are given a struct linked list, which has a head pointer that points to the first node in the list and a size which represents the length of the linked list. You also have a struct node that has a next pointer to the next list node and also a char pointer that points to a String in memory. Refer to the following diagram for a visual representation of list and list node:

2.2 Testing

Note: If you don’t want to use the docker GUI, run the cs2110 docker script with the flag -it. This will connect to docker using only the terminal, which is all you need for this homework.

To compile and test your code, use the Makefile given as follows:

To manually test specific methods in your code, fill in the main method in main.c with tests, and run

make hw9

This will create an executable called hw9. Then, run the main method using

./hw9

To run the autograder, run

make run-tests

The local autograder does not test for memory leaks, though the one on gradescope does. To test your code for memory leaks locally, you will need to use valgrind.

To test your code using valgrind, run

make run-valgrind

3 Deliverables

Your only deliverable is the list.c file.

The is what you need to submit to gradescope.

4 Appendix

4.1 Appendix D: Rules and Regulations

4.1.1 General Rules

1. Starting with the assembly homeworks, any code you write should be meaningfully commented for your benefit. You should comment your code in terms of the algorithm you are implementing; we all know what each line of code does.

3. Please read the assignment in its entirety before asking questions.

5. If you find any problems with the assignment it would be greatly appreciated if you reported them to the author (which can be found at the top of the assignment). Announcements will be posted if the assignment changes.

4.1.2 Submission Conventions

1. All files you submit for assignments in this course should have your name at the top of the file as a comment for any source code file, and somewhere in the file, near the top, for other files unless otherwise noted.

3. Do not submit compiled files, that is .class files for Java code and .o files for C code. Only submit the files we ask for in the assignment.

4. Do not submit links to files. The autograder does not understand it, and we will not manually grade assignments submitted this way as it is easy to change the files after the submission period ends.

4.1.3 Submission Guidelines

2. You are also responsible for ensuring that what you turned in is what you meant to turn in. After submitting you should be sure to download your submission into a brand new folder and test if it works. No excuses if you submit the wrong files, what you turn in is what we grade. In addition, your assignment must be turned in via Canvas/Gradescope. Under no circumstances whatsoever we will accept any email submission of an assignment. Note: if you were granted an extension you will still turn in the assignment over Canvas/Gradescope.

4.1.4 Syllabus Excerpt on Academic Misconduct

Academic misconduct is taken very seriously in this class. Quizzes, timed labs and the final examination are individual work.

Homework assignments are collaborative, In addition many if not all homework assignments will be evaluated via demo or code review. During this evaluation, you will be expected to be able to explain every aspect of your submission. Homework assignments will also be examined using computer programs to find evidence of unauthorized collaboration.

You are expressly forbidden to supply a copy of your homework to another student via electronic means. This includes simply e-mailing it to them so they can look at it. If you supply an electronic copy of your homework to another student and they are charged with copying, you will also be charged. This includes storing your code on any site which would allow other parties to obtain your code such as but not limited to public repositories (Github), pastebin, etc. If you would like to use version control, use github.gatech.edu

4.1.5 Is collaboration allowed?

Figure 1: Collaboration rules, explained colorfully
