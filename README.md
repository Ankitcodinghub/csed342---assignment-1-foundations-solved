# csed342---assignment-1-foundations-solved
**TO GET THIS SOLUTION VISIT:** [CSED342 – Assignment 1. Foundations Solved](https://www.ankitcodinghub.com/product/csed342-assignment-1-foundations-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115853&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSED342 - Assignment 1. Foundations Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Hwanjo Yu

CSED342 – Artificial Intelligence

General Instructions

This (and every) assignment has a written part and a programming part.

You should write both types of answers in submission.py between

# BEGIN_YOUR_ANSWER and

# END_YOUR_ANSWER

ÒThis icon means a written answer is expected. Some of these problems are multiple choice questions that impose negative scores if the answers are incorrect. So, don’t write answers unless you are confident.

¥This icon means you should write code. you can add other helper functions outside the answer block if you want. Do not make changes to files other than submission.py.

Your code will be evaluated on two types of test cases, basic and hidden, which you can see in grader.py. Basic tests, which are fully provided to you, do not stress your code with large inputs or tricky corner cases. Hidden tests are more complex and do stress your code. The inputs of hidden tests are provided in grader.py, but the correct outputs are not. To run all the tests, type

python grader.py

This will tell you only whether you passed the basic tests. On the hidden tests, the script will alert you if your code takes too long or crashes, but does not say whether you got the correct output. You can also run a single test (e.g., 3a-0-basic) by typing

python grader.py 3a-0-basic

We strongly encourage you to read and understand the test cases, create your own test cases, and not just blindly run grader.py.

Problems

Problem 1. Optimization and probability

In this class, we will cast AI problems as optimization problems, that is, finding the best solution in a rigorous mathematical sense. At the same time, we must be adroit at coping with uncertainty in the world, and for that, we appeal to tools from probability. Read the following problems and write your answers in submission.py.

Problem 1a [3 points] Ò

Suppose the probability of a coin turning up heads is 0 &lt; p &lt; 1, and that we flip it 5 times and get {H,T,H,T,T}. We know the probability (likelihood) of obtaining this sequence is L(p) = p(1 − p)p(1 − p)(1 − p) = p2(1 − p)3. Now let’s go backwards and ask the question: what is the value of p that maximizes L(p)?

Hint: Consider taking the derivative of logL(p). Taking the derivative of L(p) works too, but it is cleaner and more natural to differentiate logL(p). You can verify for yourself that the value of p which minimizes logL(p) must also minimize L(p).

Problem 1b [3 points] Ò

Let’s practice taking gradients, which is a key operation for being able to optimize continuous functions. For w ∈Rd and constants ai,bj ∈Rd and λ ∈R, define the scalar-valued function

n n

f(w) = XX(a&gt;i w − b&gt;j w)2 + λkwk22,

i=1 j=1

where the vector is w = (w1,…,wd) and is known as the L2 norm.

Compute the gradient ∇wf(w).

Recall: the gradient is a d-dimensional vector of the partial derivatives with respect to each wi:

.

What’s the formula for the gradient? Choose one of the following expressions:

w w w w

• u

• w

• ∂w∂&gt;wMw = (M + M&gt;)w where w and u are vectors and M is a matrix.

Problem 2: Programming

In this problem, you will implement a bunch of short functions. The main purpose of this exercise is to familiarize yourself with Python, but as a bonus, the functions that you will implement will come in handy in subsequent homeworks.

If you’re new to Python, the following provide pointers to various tutorials and examples for the language: • Python for Programmers:

https://wiki.python.org/moin/BeginnersGuide/Programmers • Example programs of increasing complexity:

https://wiki.python.org/moin/SimplePrograms

Problem 2a [4 points] ¥

Implement getWordKey for computeMaxWordLength in submission.py.

Problem 2b [3 points] ¥

Implement manhattanDistance in submission.py.

Problem 2c [7 points] ¥

Implement countMutatedSentences in submission.py.

Problem 2d [2 points] ¥

Implement dotProduct in submission.py.

Problem 2e [2 points] ¥

Implement incrementSparseVector in submission.py.

Problem 2f [3 points] ¥

Implement computeMostFrequentWord in submission.py.
