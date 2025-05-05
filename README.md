# cse102-assignment-2-decision-trees-in-c-solved
**TO GET THIS SOLUTION VISIT:** [CSE102 Assignment 2-Decision trees in C Solved](https://www.ankitcodinghub.com/product/cse102-assignment-2-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101980&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE102 Assignment 2-Decision trees in C Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<div class="layoutArea">
<div class="column">
In this assignment, you will learn how to implement decision trees in C and compare their performances.

A decision tree is a simple model for classification and regression in machine learning. It gives the steps of a set of comparisons to come up with a a decision on a given input. For example, if you want to build a system to automatically turn on the heater in a room based on several inputs, you can use the following decision tree.

Given temperature(t), pressure(p), humidity(h), sunny_or_not(s) and day_of_the_week(w) as your input, this decision tree answers wheter or not to turn on the AC (0=turn off, 1=turn on).

Complete the code in the given project with the following tasks:

<ol>
<li>main.c: In the main function you will be solving three problems using two decision trees for each. Your program will ask which problem to solve (1, 2 or 3). Based on the answer, user’s inputs will be read (as many as required with the right types). The input will be processed by the two alternative decision trees (you will implement these in functions as described below). The results will be compared and the final result will be printed. In the case of classifier (output is a number from a set of possibilities), if both answers are the same, that result will be given as the answer to the problem. If the results differ, both decisions will be reported. Similarly, for regression (the output is an ordinal number), if the two results are similar (within a threshold, defined as the constant CLOSE_ENOUGH in util.h), the average will be printed otherwise both results will be output.</li>
<li>util.c (and util.h): There are six functions in this file. Each pair of functions are solutions to the same problem. First four decision trees are given in the figures below. The last two are supposed to be designed by you in the following manner:
<ol>
<li>The decision trees will solve a classification problem.</li>
<li>It should have at least 10 decision nodes.</li>
<li>The input should be 5 dimensional with two real numbers and 3 categorical (one binary,the others with more than 5 possible values).</li>
<li>Each of these inputs should at least once used in the decision nodes.</li>
<li>Provide two significantly different such trees and implement them in dt3a and dt3b.</li>
</ol>
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
Page 1 of 3

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
CSE102 – Spring 2022 Assignment #2

</div>
</div>
<div class="layoutArea">
<div class="column">
General Rules:

<ul>
<li> &nbsp;Obey the style guidelines.</li>
<li> &nbsp;Do not change the provided function prototypes (you will not get any credits).</li>
<li> &nbsp;The program must be developed on Ubuntu using GCC compiler (version provided in class),compilation problems due to the use of another OS or compiler is your responsibility (you will
not get any credits).
</li>
<li> &nbsp;Your program should work as expected. Do not expect partial credit if your code works only insome cases but not in all cases as expected.</li>
<li> &nbsp;You can ask your questions about the homework by positing on the forum in Teams.Handing in your work:
<ul>
<li> &nbsp;Hand in your work using the appropriate class Teams assignment site.</li>
<li> &nbsp;No late submissions will be accepted.</li>
<li> &nbsp;Please pack your solution directory in the following way (assuming a student with number20180000001 and name X Y Z is submitting):</li>
</ul>
</li>
</ul>
o A directory named 20180000001_X_Z is created

o All the solutions files along with a make file are created as part of the assignment. For

example:

o Pack this directory into a zip file named 20180000001_X_Z.zip

o When unpacked as above in Ubuntu (version provided in class) it should allow executing

the following commands in a shell:

<ul>
<li> &nbsp;“$make clean” removes everything except makefile, source code (.c and .h) andother resource files (if any) – all compiling results and intermediate files should
be removed.
</li>
<li> &nbsp;“$make compile” should compile the code.</li>
<li> &nbsp;“$make run” should run the code along with any parameters needed.The first decision tree for P1:</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Page 2 of 3

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
CSE102 – Spring 2022 Assignment #2 The second decision tree for P1:

The first decision trees for P2:

The second decision trees for P2:

</div>
</div>
<div class="layoutArea">
<div class="column">
Page 3 of 3

</div>
</div>
</div>
